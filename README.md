# nsx-tier-viewer

Welcome to the NSX Tier Viewer project!
The goal of this code is to provide a quick, simple visual representation of an NSX environment.

### Prerequisites:

* A target NSX Manager VM
* Ruby installed on the local system
* A web browser

### How To Use This Tool:

* Edit the NSX Manager VM $url, $port, $user, and $pass in 'credentials.rb'
```
$url='0.0.0.0'
$port='443'
$user='admin'
$pass='password'
```
* Run 'script.rb' and then open 'index.html' (Windows users can just run 'runme.bat' instead)
* 'index.html' should display the NSX topology