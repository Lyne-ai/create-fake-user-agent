# create-fake-user-agent

One of the biggest issues with user agents is that they're very easy to flag, especially if you're using an already suspicious IP address. Lying about user agents is not unique, and it's very easy for a site to figure out that you're lying. So instead of lying about having a user agent they already know about, might as well lie about a user agent they've never seen before.

This simple function creates a random user agent that, while unknown, will not raise any suspicions because it'll be only used once!  

Examples:  
{'User-Agent': 'veyeramo/0.3 (http://veyeramo.io)'}  
{'User-Agent': 'miruki/1.0 (http://miruki.net)'}  
{'User-Agent': 'jixibaxuziro/2.8 (http://jixibaxuziro.com)'}  
