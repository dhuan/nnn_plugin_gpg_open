# gpg_open

- Extends NNN to open GPG-encrypted files.
- No new files are created in your current directory upon decryption - this simply opens the file.

## Installation and usage

Download and place the plugin utility into NNN's plugin folder:

```sh
$ cd ~/.config/nnn/plugins
$ wget https://raw.githubusercontent.com/dhuan/nnn_plugin_gpg_open/master/gpg_open
$ chmod u+x ./gpg_open
```

Make the utility usable in NNN, binded to your preferred key:

```sh
$ export NNN_PLUG="x:gpg_open"
```

With that, in NNN, pressing the PLUGIN key will open any GPG-encrypted file that you've selected.

## LICENSE

MIT License

Copyright (c) 2022 Dhuan Oliveira

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

