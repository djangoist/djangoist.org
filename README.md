We use tornado.

<https://an-experiment.com/>

- [burningalot](https://static.djangoproject.com/img/fundraising-heart.cd6bb84ffd33.svg)
- [pillisi, cerceveli](https://github.com/djangoist/djangoist.org/blob/master/burning.svg)
- [cercevesiz](https://raw.githubusercontent.com/djangoist/djangoist.org/master/burning.svg)

We can use django too but it gives 404 to be honest.

# Deductive reasoning

 - https://djangoproject.com/404/ (Gives 404, Not found)
 - https://djangoproject.com/402/ (Gives 404, Not found)
 - https://djangoproject.com/500/ (Internal Server Error, so let it play "Gözlerimin içinde")

Also
 - https://djangoproject.com/istanbul/ (Gives 404)

Therefore
 - https://djangoproject.com/500/ is really giving 500 and sending error emails.

We're making a GET request. So, a 500 error for such an error is a little bit brutal.

Also, https://djangoproject.com/LETSREMOVEIT.txt, gives 200 with the following content.

    User-agent: *
    Disallow: /someurl
    
Do we really need to tell them that we have an admin panel exactly at that URL?
This is 2021, you can't disallow anybody by just telling "disallow".
