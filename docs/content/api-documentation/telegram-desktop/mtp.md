<!-- vim: syntax=Markdown -->

# MTP

## Table of Contents

* [MTP](#td.mtp.MTP)
  * [Environment](#td.mtp.MTP.Environment)
  * [RSAPublicKey](#td.mtp.MTP.RSAPublicKey)
  * [DcOptions](#td.mtp.MTP.DcOptions)
    * [Address](#td.mtp.MTP.DcOptions.Address)
    * [Protocol](#td.mtp.MTP.DcOptions.Protocol)
    * [Flag](#td.mtp.MTP.DcOptions.Flag)
    * [Endpoint](#td.mtp.MTP.DcOptions.Endpoint)
  * [ConfigFields](#td.mtp.MTP.ConfigFields)
  * [Config](#td.mtp.MTP.Config)

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L1)

<a id="td.mtp.MTP"></a>

## MTP Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L9)

```python
class MTP(BaseObject)
```

MTProto Protocal
https://core.telegram.org/mtproto

<a id="td.mtp.MTP.Environment"></a>

## Environment Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L16)

```python
class Environment(IntEnum)
```

Enviroment flag for MTP.Config

<a id="td.mtp.MTP.RSAPublicKey"></a>

## RSAPublicKey Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L23)

```python
class RSAPublicKey(BaseObject)
```

To be added

<a id="td.mtp.MTP.DcOptions"></a>

## DcOptions Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L28)

```python
class DcOptions(BaseObject)
```

Data Center Options, providing information about DC ip, port,.. etc

<a id="td.mtp.MTP.DcOptions.Address"></a>

## Address Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L167)

```python
class Address(int)
```

Flag used for MTP.DcOptions.Endpoint

<a id="td.mtp.MTP.DcOptions.Protocol"></a>

## Protocol Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L174)

```python
class Protocol(int)
```

Flag used for MTP.DcOptions.Endpoint

<a id="td.mtp.MTP.DcOptions.Flag"></a>

## Flag Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L181)

```python
class Flag(int)
```

Flag used for MTP.DcOptions.Endpoint

<a id="td.mtp.MTP.DcOptions.Endpoint"></a>

## Endpoint Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L193)

```python
class Endpoint(BaseObject)
```

Data center endpoint information

<a id="td.mtp.MTP.ConfigFields"></a>

## ConfigFields Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L205)

```python
class ConfigFields(BaseObject)
```

Configuration data for MTP.Config

<a id="td.mtp.MTP.Config"></a>

## Config Objects

[[source]](https://github.com/thedemons/opentele/blob/c9036f76e4d63f9d6977e997a75bc17909c78d5a/src\td\mtp.py#L241)

```python
class Config(BaseObject)
```

Configuration of MTProto
