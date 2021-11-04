# insecure-target-blank-sample

Insecure target="_blank" links sample.

## How to try

```sh
# clone
git clone https://github.com/shinshin86/insecure-target-blank-sample.git
cd insecure-target-blank-sample

# Start the local server (here we are running Python3)
python -m http.server 3000 # access => localhost:3000
```

When you click on the insecure link, an unintended URL ( `./index3.html` ) will be given to `window.opener.localtion` in the destination page.
You will see that the page from which you are transitioning has changed.

