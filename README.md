python-bittrex
==============

These are Python bindings for the official Bittrex API.

**Note: I am not associated with Bitttrex and this is an _unofficial_ API wrapper.**

Use at your own risk.

Tips are appreciated:
* BTC: 1Lc5N89huRT4aBxahNEMkCzVx7DUDAgem2
* LTC: LQJ8sjD7YZ7YgWajLtaYwn5xbUahFLsgFo
* DOGE: DQtoZeA4y5y8ZN9Hezw7sy9GQkGCRjzyK7

### Installation

To install, use `pip` with `setuptools` installed: `pip install bittrex`.

Alternatively, you can clone the GitHub repository:

```bash
git clone https://github.com/panchr/python-bittrex.git
python setup.py install
```

### Testing

In order to run the integration tests, a file called "secrets.json" must be added to the test folder.
Structure it as follows, adding your API keys:
```
{
  "key": "mykey",
  "secret": "mysecret"
}
```