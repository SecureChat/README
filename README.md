## README

Imagine we want to send our bank account numbers and their passwords to our relatives. What application can we use? Is it sure that the service provider will not monitor or leak our information?

You might say that the application you are using is safe according to the service providers. Are they telling you they use end-to-end encryption or some other "fancy" techniques? Then try to answer this question, **"What if they add backdoors in their applications?"**

Moreover, you might ask whether it is safe if we use voice messages instead of texts. **If you are able to edit texts with speech recognition techniques, the service providers are able to do so, too.**

Since we cannot get full access to the source code of current social platforms and instant message applications, a fully open sourced social platform may be the only method to protect our information.

There were many open source projects that tried to offer an alternative to the mainstream social platforms. But as far as we know, none of them succeeded.

Generally speaking, there are two categories of such open source methods. The first category of methods generates a unique ID with the application and uses this ID to identify the user. Besides some technical issues, the main problem of this category of methods is that it is difficult to add friends since the ID is isolate with other contact information of the friends. The second category of methods uses XMPP services. Besides some technical issues, one big problem is that there isn't many reliable free XMPP servers. **These methods are all great in terms of technology, but a successful application is not all about technology.**

Having reviewed many of the existing products and considered the problem of feasibility, we proposed a _Self-Organized Social Network Based on Emails_.

Email service is one of the most widely used free services on the Internet. It is even possible for an individual user to establish his/her own email server. In addition, Email service provides an extra layer in the communication process, which allows users to edit texts by themselves. Taking advantage of this extra layer, we may encode the content of our email to protect our private information.

From another perspective, our solution can be viewed as an Email client. By showing nothing but emails relevant to our application, it filters out many trash Emails and makes the email reading experience much better.

We view our project as a complementary of mainstream social platforms, an introduction to other technically advanced decentralized communication solutions and a trade-off between easy accessibility and technology.

<p align='center'>04/13/2016<br>Peidong Wang</p>
