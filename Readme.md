
# Vagrant-Ansible-Windows

**Ansible and Windows are sitting in a tree and p-r-o-v-i-s-i-o-n-i-n-g!**

# Why?

Have you ever had to install Ansible on Windows instead of a lovely Linux machine?
And you'll need to install it if you want to simply ```vagrant up``` with the Ansible provider enabled.
Let's skip this step and spin up multiple connected virtual machines with the help of *Vagrant*.
Thereby we can use one instance as the ```[master]``` and the other one as the ```[slave]```.

# Dependencies

- [Virtualbox](https://www.virtualbox.org/)
- [Vagrant](http://www.vagrantup.com/)
- If it is not possible for you to run 64-Bit boxes, you could easily change the ```Vagrantfile``` to ```"precise32.box"```

# Installation

    $ git clone https://github.com/meggesje/vagrant-ansible-windows.git
    $ cd vagrant-ansible-windows
    $ vagrant up [master | slave]

# License

The MIT License (MIT)

Copyright (c) 2013 Marcus André <meggesje@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.