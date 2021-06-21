# The Giki Philosophy

The Giki Philosophy is an approach to making it easier to decentralise the work of the maintaining the website, even allowing conference
attendees to fix errors they find in your site, whilst maintaining central control.

The trick is to make it convenient for people to edit your pages directly in github's on line editor, and provide you with a pull request.

This is relatively simply done through a set of 'edit' links that appear on relevant pages. For example, if you go to the [AISTATS 2019 webpage](http://aistats.org/aistats2019) 
you will find just below the initial title a link to the side saying [edit]. This link leads directly to the `_config.yml` for the AISTATS 2019 
page, opening the dit page. If a user is not logged into their github account, they will be asked to do so. Editing automatically forks the repo
into their github account. They can now submit a pull request to request updates.

The giki philosophy uses this convenience to share the workload of correcting errors and maintaining the site. It has most widely been put
to use on the PMLR website, where AISTATS proceedings have been published since 2007. If you encourage attendees to make use of the giki links
then you can significantly reduce the maintanance load. You may also find the giki links helpful yourself for making minor fixes to errors that 
you spot. Such fixes can even be made from mobile phones or tablets.
