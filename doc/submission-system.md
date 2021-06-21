## Submission System

One of the most critical decisions you will make will be the conference submission system that you use.

This system is used for managing submissions of papers, allocation of reviewers and area chairs. 

It is one of the most critical decisions you will make, but I've never heard anyone state that there is a perfect submission system. They each have strong points and weak points. 

If you have had experience of organising a conference before you may have a preferred system. But beware, AISTATS has grown in recent years, and systems that work well for small conferences can struggle with larger conferences.

Some common systems are

* [Microsoft CMT3](https://cmt3.research.microsoft.com/About)
* [Open Review](https://openreview.net/about)
* [EasyChair](https://easychair.org/)

Since 2011, CMT has been used for AISTATS. The switch to CMT was driven by the increase in paper numbers. But it is worth speaking to colleagues who've recently organised a meeting to check their experience. Some systems (such as OpenReview) assume a particular style of review. 

Once you have made your choice, you will need to request a URL for your submissions. Once you have that URL you can edit the following fields in the [`_config.yml`](_config.yml) file:

```
conference:
  submission:
    # Whether to show the submission site.
    show: 
    # The URL of the submission site.
    url: 
    # The name of the submission site (e.g. Microsoft CMT Website)
    name: 
```

That will auto generate some text in the `submit.html` page. You can fill in details around submission on that page and it will appear below. 
