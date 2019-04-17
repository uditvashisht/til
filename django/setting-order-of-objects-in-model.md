# How to set order of objects in a Model?

Create an inner class Meta in the model and set ordering as under:-

```
class Movie(models.Model):

    class Meta:
        ordering = ('-year' , 'title')
```

This will order the movies in decreasing order of year and then in each year alphabetically (by title).

