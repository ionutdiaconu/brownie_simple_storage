install pipx
    python -m pip install --user pipx
    python -m pipx ensurepath

install Brownie
    pipx install eth-brownie
    or
    py -m pipx install eth-brownie

    note: brownie prerequisites
    pip install Cython
    pip install cytoolz
    pip install pybind11

    test: brownie --verion

# init project
-brownie init
-create a sol file in contracts
-brownie compile

-create a script for deplyment (in scripts folder). see deploy.py
    - brownie run scripts/deploy.py


-create a new brownie accout:
    brownie accounts new myAccount
brownie accounts list