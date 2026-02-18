# How to best approach the fullstack projects
## Don't try to finish all during the program
Simply put, you will not have time to and I do not recommend it. It is more sensible to spend your time during the formation focusing on learning and practicing the ongoing content so that when you are done, you are prepared to apply that knowledge to the projects. Waiting until the end also means that you will be able to start these projects with much more knowledge than you have right now, and you will be able to attain a *better* result in *less* time.

## Familiarize yourself with the subject early so your life is easier later
Given that you won't be doing the projects *during* the program, you should do what you can to make your life as easy as possible in the future (a few months from now). What does this mean exactly?
* Take notes on the project (see next section)
* Make sure that the workflow required by the project is clear in your mind, so that any steps you may need to employ later are things that you have seen and familiarized yourself with *during* the modules on those subjects. That way you avoid having to relearn these points without the support of teachers / TAs / your classmates.

## Take notes
### Write down the process you have in mind for the project
To make your life easier when you come back to your projects after the program, write down a clear process you can follow to complete your work. That way, you don't have to worry about forgetting all the necessary steps and tools.

For a project like Kayak, it might look something like this:
* Use a geolocalisation API to get latitude and longitude for my list of cities (such as [nominatim](https://nominatim.org/release-docs/develop/api/Overview/))
* Use a weather API to get weather information on my cities, thanks to the coordinates (such as [open weather api](https://openweathermap.org/api))
* Use my weather information to select the 5 most attractive cities for a holiday
* Use Scrapy to scrape [booking.com](https://www.booking.com/index.en-gb.html) information on 25 information for each city
* Upload all my raw data to an S3 bucket using boto3
* Retrieve the data locally using boto3
* Clean and structure the data into a tabular format with python and pandas
* Upload my tabular data to an RDS with sqlalchemy
* Run a few SQL requests on my data using sqlalchemy

**IMPORTANT NOTE:** Take screenshots and make backups of your work! This is important for 2 reasons:
* Some projects have notoriously unstable elements (such as web scraping) that may stop working from one day to another. With screenshots and backups, you only need to make it work once to be able to present it to the jury months later.
* Some projects use costly cloud services (S3, RDS). Screenshots allow you to close the service after you've finished and not risk paying for months of (useless) activity.

### Write down a list of concrete goals so you know when you're done

It is very easy to go overboard and fall down a rabbit hole while working on your projects. It's good idea to take some time after having discovered and understood the project to write down a concise and objective-oriented list of goals that you **need** to complete to be able to finish the project. That way, once you have successfully checked off all the elements of your list, you know that you can consider a project finished (even if you are tempted to continue working on certain aspects).

* What tools do you have to use?
* What processes do you need to put into place?
* What questions do you need to answer?
* What problems do you need to solve?
* What specific files do you need hand in for the certification?

To answer these, you must understand what is asked of you to certify the project. Please pay special attention to the project pages that often have listed criteria (eg. for Tinder [Tinder Project Page](https://app.jedha.co/course/project-speed-dating-ft/speed-dating-ft)) and to look at the specific block of the [certification](https://app.jedha.co/course/become-certified-machine-learning-engineer-ft/machine-learning-engineer-certificate-ft) you will be validating to see what criteria are asked of you. They do not correspond *exactly* to the evaluation grid that will be used to judge your work, but they will give you a very good set of goals to try to meet.

*End note:*
*There is nothing wrong with wanting to continue working on a project and improving it, as long as you are aware of whether or not it is actually beneficial to you to spend your time on it with regards to the certification. I recommend trying to focus on completing the projects to a standard degree for the certification and reserving any further explorations for after your jury passages. You can then continue to work on these aspects on your own time, and show off your work as personal projects in your portfolio while looking for work!*