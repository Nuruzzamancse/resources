<a href="https://newtonx.atlassian.net/wiki/spaces/~182496084/pages/1342636033/Python+Environment+Setup">Confluence page</a>
<br/>
<a href="https://github.com/pyenv/pyenv">Pyenv</a>
<br/>
<a href="https://virtualenvwrapper.readthedocs.io/en/latest/">virtualenvwrapper</a>
<br/>
<a href="https://newtonx.atlassian.net/wiki/spaces/DEVOPS/pages/2374008833/Using+PyPi+private+repositories+for+sharing+Python+libraries">private library issue fix</a>

<pre>
python -m venv env
sourc env_name/bin/activate
</pre>

.bashrc/.zshrc profile contents for Linux
<br/>
<pre>
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv virtualenv-init -)"
export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
source /usr/local/bin/virtualenvwrapper.sh
</pre>

<pre>
pyenv install 3.8.9
pyenv global 3.8.9
</pre>

<pre>
pip install --no-input keyring
pip install --no-input keyrings.google-artifactregistry-auth
</pre>