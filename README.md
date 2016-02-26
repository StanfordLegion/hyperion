# hyperion
Performance regression tests for the Legion project


## Setup

### Install 3x
We currently use a wacky patched version, so its best to just copy it from me into your home folder.

For manual exploaration you might want to put 3x's bin directory on your path by addiing this to your shell config (e.g. ~/.bashrc): `PATH=~/3x/@prefix@/bin:"$PATH"`.

### Install legion-performance workbench and cronjob

To run the setup script, you can simply execute
```
source <(curl -fsSL https://raw.githubusercontent.com/StanfordLegion/hyperion/master/setup)

```