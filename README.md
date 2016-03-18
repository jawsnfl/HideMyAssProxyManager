# HideMyAssProxyManager
A simple java program that extracts the list of proxies from Hide My Ass's webpage. This program is for educational purposes only.

#ProxyManager
A main java class that contain methods to scrape the proxy information from HideMyAss Free proxy webpage using Jsoup library.
The information of the proxies are store in an ArrayList <Proxy> and can be retrieved from the class.

Important: At the moment, our program only stores HTTP/S type proxies and not Socket4/5 proxies.

The ProxyManager has a method that tests each proxy in the list and remove any unresponsive or "bad" proxies from the list.
This will minimise effort and resources when you are using the proxy.
You can set the default response and read timeout for the class. When testing the proxies, the class will refer to the default response and read timeout. Any proxy that does not fall within the specified timeout will be removed.

At the end of the ProxyManager class, I've written usage examples in the the main class.

