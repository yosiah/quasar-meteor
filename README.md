# quasar-meteor
quasar-meteor meteor up 1.7.0.5

Install from npm

meteor npm install
Create a link to quasar-framework in the /imports directory

ln -s ../node_modules/quasar-framework imports

(If you are doing this on Windows the link command is:

mklink /D "imports\quasar-framework" "..\node_modules\quasar-framework\"
thanks to Noboxulus for working this out)
