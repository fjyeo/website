---
title: Python code work
tags:
  - code
  - python
  - jupyter
---

### An example of code

{% highlight python %}
  def metres_to_miles(time_in_seconds, distance_in_metres, name):
    
    time_in_minutes =time_in_seconds/60
    time_in_hours =time_in_minutes/60
    distance_in_miles =distance_in_metres*0.000621371
    average_miles_per_hour =distance_in_miles/time_in_hours
    final_answer = name + " = " + str(average_miles_per_hour) + " mph for " + str(distance_in_metres) + "m"  
    return final_answer
{% endhighlight %}

This is My python coding. This function (the piece of code) allowes u to put in youre time in seconds of how quick you did youre run and what lengh the run was and finally allowes you to put youre name. The computer will ask for those three things.

{% highlight python %}
  freddies_80m= metres_to_miles(12.64,80, "Freddie Yeo")
  freddies_80m
{% endhighlight %}

This is what you return to the computer so it can give you the answer. 

{% highlight python %}
'Freddie Yeo = 14.157820253164557 mph for 80m'
{% endhighlight %}

This is the answer the computer gives you. 

Thank you for continuing to look at my website.
Bye

