# sQu1rr's Overlay

## Contents

### rxvt-unicode (9.22)

#### Description
urxvt terminal emulator with full truecolor (24bit) support
[patch](https://github.com/spudowiar/rxvt-unicode).

To enable 24bit colour add 24bit use flag for rxvt-unicode

*More patches are planned in the future*

#### Testing colour support
[This script](https://raw.github.com/sQu1rr/sQu1rr-overlay/assets/bash/truecolours.sh)
will test for terminal colour support

Without 24bit use flag:

![alt tag](https://raw.github.com/sQu1rr/sQu1rr-overlay/assets/img/urxvt-wo.png)

With 24bit use flag:

![alt tag](https://raw.github.com/sQu1rr/sQu1rr-overlay/assets/img/urxvt-w.png)

# Using

Add overlay with layman
```bash
layman -o https://raw.github.com/sQu1rr/sQu1rr-overlay/master/repositories.xml \
       -f -a sQu1rr
```

And (re)install urxvt
