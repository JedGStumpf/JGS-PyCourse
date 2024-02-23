---
title: intorduction_to_variables

---


# Introducing Variables

<!-- <img src="./goal.png" alt="Your Goal" style="float: right; width: 200px; margin-bottom:20px; "/> -->

With this lesson we will learn about the usefulness of variables for storing data and a quick intro on how we can sometimes change the type of data that is being stored.

# Assignment

Read each of  the comments in the code carefully for instructions. 

<iframe width="100%" height="600" src="https://trinket.io/tools/1.0/jekyll/embed/python#code=%22%22%22%0AA%20variable%20is%20a%20placeholder%20for%20information.%20Unlike%20some%20other%20programming%20languages%2C%20they%20are%20very%20simple%20to%20create%20in%20Python%20because%20you%20do%20not%20need%20to%20know%20what%20type%20of%20data%20you%20are%20storing.%0A%0AGive%20the%20variable%20a%20name%20%28any%20name%20works%20as%20long%20as%20it%20starts%20with%20a%20letter%29%20and%20then%20use%20%60%3D%60%20to%20give%20it%20a%20value.%0A%22%22%22%0A%0A%23%23%20Examples%3A%0Adogs_name%20%3D%20%22rufus%22%0Amy_age%20%3D%2019%0Auser_id%20%3D%201234567890%0A%0A%23%20Once%20a%20variable%20has%20been%20given%20a%20value%2C%20that%20value%20can%20be%20used%20in%20later%20parts%20of%20the%20program.%0A%0A%23%23%20Examples%3A%0A%0Aprint%28%22My%20dog%27s%20name%20is%20%22%20%2B%20dogs_name%29%0Ayear_of_birthBirth%20%3D%202024%20-%20my_age%0Aprint%28year_of_birthBirth%29%0A%0A%0A%23%20Sometimes%2C%20however%2C%20you%20do%20need%20to%20know%20what%20type%20of%20data%20you%20are%20holding.%20Look%20at%20the%20following%20example%20and%20guess%20what%20the%20output%20will%20be.%0A%0A%0Anum1%20%3D%20input%28%22Enter%20a%20number%22%29%0Anum2%20%3D%20input%28%22Enter%20another%20number%22%29%0Asum%20%3D%20num1%20%2B%20num2%0Aprint%28%22The%20sum%20is%3A%20%22%20%2B%20sum%29%0A%0A%0A%23%20If%20the%20input%20is%205%20for%20num1%20and%2010%20for%20num2%2C%20the%20output%20would%20be%20510%20instead%20of%2015.%20So%20in%20this%20case%20you%20would%20need%20to%20convert%20num1%20and%20num2%20into%20an%20integer%20using%20the%20%60int%28%29%60%20function.%0A%0A%0Anum1%20%3D%20input%28%22Enter%20a%20number%22%29%0Anum2%20%3D%20input%28%22Enter%20another%20number%22%29%0Aif%20num1.isdigit%28%29%20and%20num2.isdigit%28%29%3A%0A%20%20%20%20sum%20%3D%20int%28num1%29%20%2B%20int%28num2%29%0A%20%20%20%20print%28f%22The%20sum%20is%3A%20%7Bsum%7D%22%29%0Aelse%3A%0A%20%20%20%20print%28%22Please%20enter%20a%20valid%20number%22%29%0A%0A%0A%23%20The%20opposite%20is%20also%20true.%20The%20following%20example%20will%20cause%20an%20error%20because%20you%20cannot%20combine%20integer%20data%20with%20string%20data.%20%20Delete%20the%20%23%20in%20front%20of%20the%20print%20and%20run%20the%20code%20to%20see%20the%20error.%0A%0A%0Aval%20%3D%2015%0A%23%20print%28%22The%20value%20is%20%22%20%2B%20val%29%0A%0A%0A%23%20To%20make%20this%20work%2C%20val%20must%20be%20converted%20to%20a%20string%20using%20the%20%60str%28%29%60%20function.%0A%0Aval%20%3D%2015%0Aprint%28%22The%20value%20is%20%22%20%2B%20str%28val%29%29%0A%0A%0A%23%20In%20summary%2C%20variables%20are%20a%20way%20to%20store%20information%20in%20a%20program.%20They%20can%20be%20used%20to%20store%20any%20type%20of%20data%20and%20can%20be%20used%20in%20later%20parts%20of%20the%20program.%20They%20can%20also%20be%20converted%20to%20different%20types%20of%20data%20using%20the%20%60int%28%29%60%2C%20%60str%28%29%60%2C%20and%20%60float%28%29%60%20functions.%0A%0A%23%20Task%3A%20Create%20more%20variables%20and%20print%20them%20out.%20Try%20to%20use%20different%20types%20of%20data%20and%20convert%20them%20to%20other%20types%20of%20data." frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Have fun!
