# HideMyAssProxyManager
A simple java program that extracts the list of proxies from Hide My Ass's webpage. This program is for educational purposes only.

HideMyAssProxyManager is a java class that scrapes the proxy information from HideMyAss Free proxy webpage using Jsoup library.
This class creates and store the Proxy information in an Array of Proxy instances. The ProxyManager also has a method which will test
each proxy in the ArrayList and remove any unresponsive or "bad" proxies from the list. This will minimise effort and errors later one and also 
free up resources. You can set the Maximum response and read time for class. This will remove any proxies with connection time or readtime
longer than the specified (in milliseconds).

At the end of the ProxyManager class, I've written usage examples in the the main class.

