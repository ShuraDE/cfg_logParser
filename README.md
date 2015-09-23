# cfg_logParser
for https://github.com/ShuraDE/cfgObjects.VR<br/>
<br/>
alpha version<br/>
<br/>
commandline:<br/>
logParserGA.exe [import file with path] [max items per page] [wiki siteprefix]<br/>
<br/>
example:<br/>
logParserGA.exe .\arma_log.txt 500 cfgObjects/<br/>
<br/>
will result in:<br/>
.\arma_classes.txt (list of all handled classnames)<br/>
.\arma_objects.txt (xml file contains all data)<br/>
.\arma_wiki_[1-n].xml <br/>
* xml for wiki import
* used max items per page (excluding categories)
* pagename will be [prefix]classname)
