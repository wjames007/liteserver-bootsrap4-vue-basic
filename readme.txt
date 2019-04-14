npm init -y
npm install --save-dev lite-server
add "start": "lite-server" to scripts section of package.json
create an index.html
npm start

To quit type Cntrl-C

Optional:
<script src="https://cdn.jsdelivr.net/npm/vue"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>

…or create a new repository on the command line

echo "# liteserver-bootsrap4-vue-basic" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/wjames007/liteserver-bootsrap4-vue-basic.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/wjames007/liteserver-bootsrap4-vue-basic.git
git push -u origin master