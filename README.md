# gn_jax
graph networks in jax

## Setup
```shell
#  -- venv --
uv venv --python=3.12

#  -- Deps --
uv pip install -r requirements.txt

# -- Misc Finishings --

# needed for rocm jax: https://rocm.docs.amd.com/projects/install-on-linux/en/latest/install/3rd-party/jax-install.html
export LLVM_PATH=/opt/rocm/llvm

# activate venv
source .venv/bin/activate # or run everything through uv, e.g., `uv run python ...`

# strip notebooks in commit history, but not as you are working on them
nbstripout --install --attributes .gitattributes

# pre-commit setup
pre-commit install
```
