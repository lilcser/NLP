## [Install Jupyter Notebook](http://jupyter.org/install) 
### Install Jupyter Notebook with Python
Download [Anaconda](https://www.anaconda.com/download/#macos) Distribution.

### Run Notebook server
`jupyter notebook`

### Notebook Server Issue
```
*** -bash: jupyter: command not found ***

# try running the following commands:
$ sudo rm -rf /Library/Frameworks/Python.framework
$ rm /usr/local/bin/python3*
$ brew uninstall python3
$ brew install python3
$ python3 -m pip install --upgrade pip
$ python3 -m pip install jupyter
$ jupyter notebook
```

## [Standford CoreNLP](https://www.khalidalnajjar.com/setup-use-stanford-corenlp-server-python/)
### Run Standford CoreNLP Server
`java -mx4g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -port 9000 -timeout 15000`

## [py-corenlp](https://github.com/smilli/py-corenlp)
### Python wrapper for Stanford CoreNL 
You will need this to run *Python* code on *Jupyter* using *StanfordCoreNLP*. <br>
`pip install pycorenlp`

## [Sample](https://github.com/lilcser/NLP/blob/master/sample.ipynb)
