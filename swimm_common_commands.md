Now you know how to create a tutorial that includes code snippets and therefore highly coupled with your code.
</br></br>
But what happens when the code changes (as it frequently does)? </br>
Swimm’s automatic maintenance algorithm makes documentation maintenance easy and quick. Each time you open a Doc, we scan your code for changes, to see if any of them relate to the snippets in the Doc.
</br></br>
There are three scenarios that could happen to your code — _up to date_, _outdated_, _autosync_.
</br></br>

## Up to date
If a code snippet is up to date, and hasn’t changed at all, you will see this:

![Updated snippet](https://github.com/swimmio/public/blob/master/screenshots/mantainance-uptodate.png?raw=true)
</br></br>

## Outdated
If a code snippet has changed significantly, we will alert you that it is outdated. This means that the tutorial should be edited and the outdated snippet removed or updated.

![Outdate snippet](https://github.com/swimmio/public/blob/master/screenshots/maintainance-outdated.png?raw=true)
</br></br>

## Autosync
In many cases, though the code has changed, our algorithm will determine that the change was not significant, and automatically sync the tutorial with your code. In this case, you will receive this message:

![Autosync snippet](https://github.com/swimmio/public/blob/master/screenshots/mantainance-autosync.png?raw=true)
</br></br>