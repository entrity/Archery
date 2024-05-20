## Usage

Run a simple http server in this dir.
```bash
python3 -m http.server
# Then load in browser:
# http://localhost:8000/dynamic-spine-arrow-calculator-from-3rivers-archery.html
```

## Sourcing

This was downloaded from https://www.3riversarchery.com/dynamic-spine-arrow-calculator-from-3rivers-archery.html:

```bash
wget -E -H -K -k -p 'https://www.3riversarchery.com/dynamic-spine-arrow-calculator-from-3rivers-archery.html'

cd spinecalc
wget -O 'index.php' "https://www.3riversarchery.com/spinecalc/index.php?data_only=1"

# ...and then I deleted the files downloaded from 3rd-party sites
```
