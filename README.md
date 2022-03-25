# COSC140 lab 3

## Answers to the five questions at the end of the lab description

1. p1 = Product(name="stuffed shark", price=145.00, description='soft, but with pointy teeth', minimum_age_appropriate=2, maximum_age_appropriate=43)   THEN p1.save()

2. Product.objects.all()
   
3. p1 = Product.objects.get(id=6)
p1.price = 22.50
p1.save()

4. Product.objects.get(id=6).delete()
None

5. objects = Product.objects.filter(name__icontains='stuff').filter(price__lt=10)


## Lab feedback

 * How long did you spend on this lab?
 * 1.5 hours I think? 

 * What did you think about it?  What was good?  What could be improved?
 * I liked it! I thought it was pretty neat that I could see the actual interaction with the code and the database and the website. 

## Feedback

Once you commit and submit your work to Github, I'll update this section with feedback.

