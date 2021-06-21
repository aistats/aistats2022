# Venue

The tradition for AISTATS is to select a venue with warmer weather, ideally a place where swimming is possible. As the conference gets bigger though, this may be harder.

First things first. Check with the previous chairs about how many attendees you might expect. What is the trend, is the conference growing or shrinking? Once you have an idea of capacity you can choose your venue. 

Typically AISTATS is held between April and May. The first conferences were held in January, often in Florida, but with NeurIPS occuring in early December, the conference gradually moved towards Spring and early Summer (filling a gap between NeurIPS and ICML/UAI. 

The venue and timing challenge are interdependent, but often a venue is chosen first, and then the rough timing is adjusted to best suit. Precise timing is often pinned down in discussion with the venue.

Getting the precise timing is a criticial first step, because the rest of the conference organisation can 'work backwards' from there. 

While great locations have been a feature of AISTATS, there is always a tension between an attractive location and ease of access. Traditionally, AISTATS has preferred to cater more for the locality around where it's held (e.g. it's been held in Sardinia, which is easier to access from Europe, but hard from the US, Asia, Africa, etc). 

Of course you get to put your individual stamp on the conference, but it's useful to bear these traditions in mind as guide rails. 

Once you have your venue, quietly congratulate yourself, and edit the [`_config.yml`](../_config.yml) file to update the followint fields.

```
conference:
  # Set the name of the venue (e.g. Caribe Hilton Hotel)  
  venue:
  # Give the url of the venue here.  
  venue_url:
  # Give the conference location in the form City, Country here.
  location: 
```

And of course, the date fields.

```
conference:
  dates:
  - YYYY-MM-DD
  - YYYY-MM-DD
  - YYYY-MM-DD
```
Include in this list each day that the conference will run. They will be used later for generating the [schedule](./schedule.md).

Note the use of the [ISO standard in date writing](https://en.wikipedia.org/wiki/ISO_8601), being an international conference we use international dates. All dates should be written in full, or using ISO standards. The remote theme takes care of this mostly for you. 

Other issues you may want to consider is whether you want to colocate the conference. In the past AISTATS has colocated with the Learning Workshop (the predecessor to ICLR ... believe it or not it used to be smaller than AISTATS!), Machine Learning Summer Schools, the DALI Meeting and Algorithmic Learning Theory.

Colocating can help international visitors with travel, and partnering a summer school with the conference is one way to make it easier to attend for students. But colocating does add an organisational overhead. It's best done if the organisers of the other meeting are people you trust (sometimes you might even be a co-organiser of the other meeting) and if it's clear who is deciding on the venue. In all the cases above, AISTATS decided the venue and the other group joined in. Indeed, before colocating with AISTATS the Learning Workshop habitually occurred in Snowbird, a ski resort in Utah.

[Go back to main doc README.md](./README.md)

