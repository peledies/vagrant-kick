# vagrant-kick
Easily restart services on a vagrant machine.

You can run vagrant-kick with no parameters and it will prompt you for the sevice you want to restart. Alternatvely, you can supply the service that you want to restart as a parameter.

### Install
Clone vagrant-kick
```
  $ git clone https://github.com/peledies/vagrant-kick.git ~/vagrant-kick
```
Move the vagrant-kick script somewhere accessible in your environment
```
  $ cp ~/vagrant-kick/vagrant-kick /usr/local/bin/vagrant-kick
```

### Example
```
  $ vagrant-kick
```

### Example with parameter
```
  $ vagrant-kick httpd
```
