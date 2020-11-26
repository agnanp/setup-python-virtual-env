# Setup Python 3 Virtual Environment

- Update System
<pre><code>sudo apt-get update</code></pre>
<pre><code>sudo apt-get upgrade</code></pre>

- Install Developer Tools
<pre><code>sudo apt-get install build-essential cmake unzip pkg-config</code></pre>

- Install Python 3 Development Headers
<pre><code>sudo apt-get install python3-dev</code></pre>

- Install Pip
<pre><code>wget https://bootstrap.pypa.io/get-pip.py</code></pre>
<pre><code>sudo python3 get-pip.py</code></pre>

- Install virtualenv and virtualenvwrapper
<pre><code>sudo pip install virtualenv virtualenvwrapper</code></pre>
<pre><code>sudo rm -rf ~/get-pip.py ~/.cache/pip</code></pre>

- Update ~/.bashrc 

- add the following lines to your ~/.bashrc 
<pre><code># virtualenv and virtualenvwrapper</code></pre>
<pre><code>export WORKON_HOME=$HOME/.virtualenvs</code></pre>
<pre><code>export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3</code></pre>
<pre><code>source /usr/local/bin/virtualenvwrapper.sh</code></pre>

- source ~/.bashrc
<pre><code>source ~/.bashrc</code></pre>

- Create a virtual environment
<pre><code>mkvirtualenv nan -p python3</code></pre>

- verify the virtual environment using workon
<pre><code>workon nan</code></pre>
