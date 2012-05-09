Joomla Template Textmate Bundle
===============================

Joomla Template textmate bundle is a textmate bundle for develop Joomla template.

<strong>Install with Git:</strong>
<pre>
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone git://github.com/akeyz/joomla-template-textmate-bundle.git "Joomla Template.tmbundle"
osascript -e 'tell app "TextMate" to reload bundles'
</pre>

<strong>Install without Git:</strong>
<pre>
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
wget https://github.com/akeyz/joomla-template-textmate-bundle/zipball/master
unzip akeyz-joomla-template-textmate-bundle*.zip
rm akeyz-joomla-template-textmate-bundle*.zip
mv akeyz-joomla-template-textmate-bundle* "Joomla Template.tmbundle"
osascript -e 'tell app "TextMate" to reload bundles'
</pre>

If you have any question, please email me by akey.zhang@gmail.com or you can <a href="https://github.com/akeyz/joomla-template-textmate-bundle/issues">report a bug or request a feature here</a>.