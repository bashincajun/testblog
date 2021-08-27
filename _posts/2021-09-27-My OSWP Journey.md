* * *

layout: post
title: My OSWP Journey
tags:

- Blog
- Wifi
- Certifications
    description: >
    This page is just a place holder and introduction to my blog.
    hero: https://source.unsplash.com/collection/145103/
    overlay: green
    published: true

* * *

# Intro

Before we get into it I want to preface this with the fact the OSWP has been retired and as of now does not have a replacement. With that being said I still wanted to give my experience with the practical testing format as it was my first time taking a test in this way and hopefully some of the tips will help others that are seeking to take a test is this such format.

I will not share any specific details even though this specific certification is expired as Offensive security does have strict rules about sharing information related to the course/exam.

* * *

## Course Materials/Prepping for the Test

After registering i quickly received the course materials which consisted of a PDF document, videos and a ISO of the WIFU ISO which is a version of Backtrack Linux . If you are new to how WiFi functions albeit outdated at this point the PDF guide will definitely get you started. The first 100 pages or so are quite dry but do give a very beginner friendly intro to looking at packet dumps and the basics of of the technology outlined in the course.

I chose to watch the videos and go through the PDF at same time. While this did cut out the "boring stuff" i did read back through those items after I went through the videos. I thought the videos were well done and really liked the fact that they had the attack summary at the end. I revisited the attack summary portions of the videos anytime i was working through the lab and hit a bump as kind of a refresher.

There are multiple labs in the PDF guide that cover the different attacks on both WEP and WPA enabled networks. These labs were covered in the video as well.

Now you are not given a virtual lab environment so you will have to build your own.  I already had a 2.4 ghz alfa card so only thing i had to do was order a wireless router.  I went with a D-Link DIR 601 but another option is the Netgear WNR1000v2.  I only went with the D-Link because it was cheaper at the time.  The only issue I had with my router choice is that I was unable to ever perform the ChopChop attack in the lab.

I would recommend that you go through each lab multiple times so that you can recognize each target configures and know what attack method to use. I also recommend that once you are comfortable with the labs that you try different configurations and work on attacking those. Even though the tech outlined the course is outdated it still can serve as an awesome learning experience just by working through the methodology.

* * *

## Test Time

So when it came time for my test I was very unprepared as I had a family emergency that kept me from really working through the labs as i had to travel. So I took my test from the comfort of a hotel room on not the best internet connection.

My test was scheduled for 1200 pm and I got my log on credentials at exactly that time.

You have to SSH into the environment, I chose to use Bitvise SSH client and just spawn a new terminal when needed. However there were times where i wasted time looking for the right terminal since I was just working off of my laptop screen.

You will need to take a lot of screenshots, I was completing the test from a windows laptop so I used Greenshot and set a single key to take screenshots.

It took me just under 2 hours to complete the test, which is longer than I care to admit However about 2 mins after I logged into the workstation i had a complete brain fart, forgot everything i had studied (why i recommenced folks go through the labs more than once) and spent at least 30 mins flailing in my terminal like a fish out of water.

Once I gather my thoughts I was able to successfully attack the other two targets with ease. After which i went back through and attacked all three targets again which I was glad i did as i realized i missed some screenshots.

## Tips For Practical Exams

Since the OSWP has been retired this tips are mainly around studying for a practical exam.

- Work through the labs multiple times
- Practice writing the report until you are comfortable with your own work flow
- Screenshots, screenshots, screenshots
- If there are multiple ways to accomplish the task practice and become comfortable and familiar with two.
- Write your report while you still have access to the test environment.
- If the test is a long one make sure you have plenty of snacks and drinks (CAFFEINE!!!!!!!)
- Take your time and breath
