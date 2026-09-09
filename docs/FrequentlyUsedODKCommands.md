# Frequently used ODK commands

## Updates the Makefile to the latest ODK

```console
$ sh run.sh update_repo 
```

## Recreates and deploys the automated documentation

```console
$ sh run.sh make update_docs
```

## Preparing a new release

```console
$ sh run.sh make prepare_release
```

## Refreshing a single import

```console
$ sh run.sh make refresh-%
```

Example:

```console
$ sh run.sh make refresh-chebi
```

## Refresh all imports

```console
$ sh run.sh make refresh-imports 
```

## Refresh all imports excluding large ones

```console
$ sh run.sh make refresh-imports-excluding-large
```

## Run all the QC checks

```console
$ sh run.sh make test
```

## Print the version of the currently installed ODK

```console
$ sh run.sh make odkversion
```

## Checks the OWL2 DL profile validity

(of a specific file)

```console
$sh run.sh make validate_profile_% 
```

Example:

```console
$ sh run.sh make validate_profile_hp-edit.owl
```
