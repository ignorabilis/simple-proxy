# Simple Proxy

A simple way to show websites where random rules are prohibiting them

To start the proxy start the python server from this folder (python 3 needed):

```bash
python3 -m http.server 9000
```

Then start ngrok:

```powershell
ngrok http --url=electric-tidy-griffon.ngrok-free.app 9000
```

To change the proxy just edit index.html.
