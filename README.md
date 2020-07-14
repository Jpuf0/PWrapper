# PWrapper: Politics & War API wrapper for Python
### Currently Implemented API Endpoints
* **Unauthenticated APIs:**
    - Nation API
    - Alliance API

* **Authenticated APIs:**
    - *none, work still in progress*

### Features
- Easy to use
- Object oriented *(take this with a grain of salt, it's my first OOP project xD)*
- No need worry about Alex's inability to use correct typing ðŸ™„

### Installation
~~PWrapper is now on [PyPI](https://pypi.org/project/PWrapper/), so you can just install it by doing:~~
```bash
pip install pwrapper
```

### Usage
1. Load it:
    ```py
    import PWrapper

    # default
    PWrapper.init(key = "abcdef12345")
    # use the test server
    PWrapper.load(test_server = True, key = "abcdef12345")
    ```
2. Init an object of the API you want to use:
    ```py
    from PWrapper import Nation    # so you don't have to type PnWrapper.Nation() every time

    nation = Nation(id = "[what ever you id is]")
    ```
3. Use it!
    ```py
    name = str(nation)
    cityids = nation.cityids
    color = nation.get("color")
    # etc...
    ```

### Issues or suggestions
Feel free to make a new issue [here](https://github.com/Jpuf0/PWrapper/issues) if you find any bugs, encounter any problems, or have a feature suggestion.
