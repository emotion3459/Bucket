# Scoop Bucket

[![Tests](https://github.com/emotion3459/Bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/emotion3459/Bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/emotion3459/Bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/emotion3459/Bucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add wia https://github.com/emotion3459/Bucket
scoop install wia/<manifestname>
```
