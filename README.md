python-bittrex
==============

Python bindings for bittrex.  I am Not associated -- use at your own risk, etc.

In order to run the integration tests, a file called "secrets.json"
must be added to the root folder of this distro. I.e. the same
directory as this README.
Structure it as follows, adding your API keys:
<pre>
<code>
{

  "key": "mykey",
  "secret": "mysecret"
}
</code>
</pre>

# Getting an API key

1. Enable 2FA
2. Add a key by pressing "Add Key" and choosing what you want to
   enable. Then press "Update Key" to add it.
   
# INSTALLATION

`python3 setup.py install`

