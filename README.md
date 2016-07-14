# Pixelmon-TCG-Language
=================

Language files for Pixelmon TCG

### How to contribute to the translations

First, you need an account here on GitHub.com. Go make one if you have not already!

Got an account? Next up, you need to fork this repository by clicking the Fork button up in the top right corner. This will take you to a new page after it's finished, and the URL will be something like `https://github.com/YourUsername/Pixelmon-TCG-Language`. Save that webpage, because you will probably want to go there a lot.

![Finding the Fork button](https://gyazo.com/6691b8a3855a8d74b36a65f60aa06b6d.png "Fork button location")

Now you're all set to start translating! Here's how you do it. First you need to find the language you are adding to, for this example we will look at U.S English, but obviously this will be different depending on the language you are translating TCG for. Find the .lang file for the language on _your fork's_ main page. Can't find it? Create it! You just hit `Create new file` and then copy paste everything from en\_US.lang into your created file to give yourself a starting template. Make sure you name it according to the proper language code, such as fr\_FR for French or es_MX for Mexican Spanish. If you're unsure what to call it, you should Google it to find out. 

![Create your own](https://gyazo.com/21cc9a53d330f38bc26feb1040ca02c5.png "Creating your own language file")

For now, however, let's just pretend we're working on U.S English.

![Finding the language](https://gyazo.com/53aa0dc23f58b494740ebc520c2300a3.png "Finding the language")

Once you're in the file, you will see a very long text file. To edit it, click the little pencil on the right.

![Finding the edit button](https://gyazo.com/3bd68873a87c7dcede12e3e2366a206c.png "Edit button")

From here you will go to each lang key (the text to the left of the =) and translate the text on the right of the =. It is very important you do not change what's on the left-side of the equals sign. For example, `item.itemShard.name=Orichalcum Shard` will always be `item.itemShard.name=[something]`. Changing the left side will have very bad results!
  
#### NOTE:
Inside these language files it is important to make sure all of the achievement keys are close together. Over time, more achievements will be added, and they need to all be in the same place so people can find them. Make sure that everything is properly sorted, so everything achievement related is together, and everything item related is together, and so on. Changing this order will not break the language file, but you still shouldn't do it! 

![Commit with description](https://gyazo.com/5177a6754b92bfedc8a7540eaa56d1cc.png "Commit with title")

When you are finished with your changes, down the bottom you enter a title for what you have changed, and you can also add a description if you want. Then make sure you have `Commit directly to the master branch` ticked, then press `Commit changes`.

If you see `Propose file change` instead of `Commit changes` then you are not looking at your fork!

After that, you'll want to make a 'pull request'. A pull request is what you do when you want your changes to be added to the sidemod. To make one, first go to the pull request tab, then click `New pull request`.

![Find pull request tab](https://gyazo.com/172c64285e7863f0c31ac4b6ffc495e6.png "New pull request")

After that, it will have a few confusing parts, talking about the base and head and master. Don't touch any of that stuff, just click the nice green button saying `Create pull request`. Then all you need to do is put in a helpful description, then click the `Create pull request` button to create the 'PR'. Eventually, someone with permission will check your changes and accept them into the sidemod. 

#### Updating your language files

When someone has modified the same language file as you, you won't immediately have those changes in your fork. You need to do a pull request in the opposite direction to get updates to yours. _You should do this every time you are about to translate_. First off, get back to the Pull Request screen, as you need to get up to where the confusing Head and Base stuff was. Then, change the left repository (The "base") to _your_ repository. It will do a little bit of thinking and then show a slightly different page, but then click the Compare across forks link.

![Compare across forks](https://gyazo.com/30ef4c34821dc743373f5e30027c8d3a.png "Compare across forks")

Now you just change the "head" to Pixelmon/Pixelmon-TCG-Language. What this does is moves all recent changes from the official repository into your fork. It should end up looking something like this (except instead of "Hiroku" it will have your username!)

![What it should look like](https://gyazo.com/aad89bd376b74c77426a7385592f2a28.png "What it should look like")

Create the pull request - there should be no need to change the title or description. 

![Click to create PR](https://gyazo.com/4ee8066b920c67367e3c5bd26ef87d71.png "Click the create PR button")

After you've clicked to create the pull request, it will take you to a page where you need to hit "Merge pull request" which is once again a very nice green button. 

![Merge it](https://gyazo.com/a20b9e236690c8850e1dc3c40866e106.png "Merge the PR")

Press confirm, and it's done! You've updated your fork. Happy translating!
