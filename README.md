# Skinly
[WIP] Skin-cancer recognition #AndroidDevChallenge


## Tell us what your idea is.

Skinly will help detect early-stage skin cancer. Using image classification, we plan to train a model to recognize various types of moles, making it able to predict potential melanoma.

In fact, benign moles can develop into an aggressive form of skin cancer called malignant melanoma. Dermatologists advise and train people with high risk, such as those having numerous moles or those frequently exposed to UV, to recognize signs of melanoma.

However, phones and computers can be more efficient in recognizing such signs (increase in size, change in color, irregular edges or skin breakdown). Many recent studies proved it right, achieving high-accuracy prediction models and in some circumstances even more accurate than dermatologists.

Providing those people, and the general public, with a free app capable of doing so can drastically reduce the number of deaths from melanoma ([55,000 a year](https://www.iarc.fr/wp-content/uploads/2018/07/WorldCancerReport.pdf)). We believe it’s time to scale what, till now, has been limited to research or niche-targeting paid services.

With Skinly users will be able to track and get insights about their moles, simply by naming them and taking regular photos. Having a timestamped list of photos for a single mole will make predictions even more accurate. We plan to use a CNN on-device model, powered by TensorFlow-Lite for low latency and better privacy.


## Tell us how you plan on bringing it to life. 


Training and fine-tuning the model is clearly the most challenging endeavor.

Thus, we plan to partner up with dermatology and cancer research organizations. Our data scientists will then be working closely with healthcare insiders to ensure relevant training, supervised by dermatologists.

We also intend to team up with our neighbor engineers from the CNRS (French National Centre for Scientific Research), who have already conducted [experiments](https://www.sciencedaily.com/releases/2018/05/180528190839.htm) in melanoma prediction using machine learning.

And, since data is critical for such achievement, we’re planning to solicit the [Health Data Hub](https://www.opusline.fr/en/health-data-hub-an-ambitious-french-initiative-for-tomorrows-health/), a French government initiative aiming to provide useful data to empower innovation. It includes records from health professionals and consenting patients.

Google’s help in such an adventure will be crucial. We are going to need Google engineers’ mentorship to boost building such a complex TensorFlow model. Plus, Google Cloud seems to be the most suitable training platform for our problem. Eventually, any help from Google to gather data needed for training will also be very appreciated.

It’s scheduled that our Machine Learning team will tackle this challenge from January, for 3 months till March. While December is dedicated for in-depth UX research, data gathering, and partnership.

Our native Android team will then start building Skinly by February, but first using just a mocked model until the ML team starts delivering usable artifacts.

We’re actively working on the app’s user experience. Please find [enclosed](https://invis.io/CMV2AM9ZVYJ) the current wireframes of Skinly.

![current experimental wireframes](https://i.ibb.co/8Y1dQ7H/Screen-Shot-2019-12-02-at-20-00-06.png)
###### more on https://invis.io/CMV2AM9ZVYJ 

## Tell us about you. 

We, [Fabernovel](https://www.fabernovel.com/en), are specialized in building fullstack native mobile apps. We started ten years ago, by building the official Paris subway system app. And then we carried-on building apps for other big companies (e.g. [Canal+](https://play.google.com/store/apps/details?id=com.canal.android.canal)) as long as for early-stage startups (e.g. [Elocance](https://www.elocance.com/en/)), gaining expertise and embracing what at the time was an emerging software market.

Headquartered in Paris, we also have offices in San Francisco and some other cities around France and the globe. Most of our software engineers are based in Paris and Lyon.

While we’ve been building apps for years, or interest in machine learning is relatively quite recent.

Today, besides regularly using Google’s machine learning services like the text-to-speech API or ML Kit to leverage our mobile apps experiences, we’ve also been training custom TensorFlow models from scratch.

Take Magic Mirror: we used machine learning to build a unique and interactive art experience. We created a machine learning engine, powered by TensorFlow-js, capable of matching postures of people in a picture with the most similar art painting.

![Magic Mirror in action @ Fabernovel HQ - Paris](https://i.ibb.co/b6b5yFn/img-20190605-160327.jpg)
###### Magic Mirror in action @ Fabernovel HQ - Paris

In addition to software technical expertise, we also have a wide team of UX/UI designers. Since our clients don’t always have a clear idea of what they need, we help them craft a solution, step-by-step and through UX workshops, ending up with a more elaborated app idea. Then, we conduct research about usability with real users before building the high-fidelity mockups and wireframes.

At Fabernovel, we deeply believe technology should serve mankind. For instance, in an effort to make the world more inclusive, we collaborated with non-profit organizations to help visually impared children read, using technology. More details [here](https://www.fabernovel.com/en/clients/cases/tib-on-tab).

This project is an opportunity for us to learn a lot while making the world a better place.


#### Complete cover letter [here](https://docs.google.com/document/d/1VgRLRZA-I2xigD_eB0TBwqxu9BkF_BZBSnVdC8RCqvc/edit?usp=sharing)
