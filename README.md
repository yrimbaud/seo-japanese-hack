# Japanese Keyword Hack Removal Process


This guide outlines a process to help identify and remove all URLs listed by Google that display Japanese pages.

This process is specifically designed to address the "Japanese Keyword Hack," a type of SEO spam where hackers inject pages with Japanese text onto a website in order to manipulate search engine rankings. 

## What is the "Japanese Keyword Hack"?

The "Japanese Keyword Hack" is a type of SEO (Search Engine Optimization) attack often perpetrated against websites with weaker security. The hacker injects a large amount of pages filled with irrelevant, typically Japanese, keywords and links into a vulnerable website.

This attacks has 2 purposes:

- Manipulate search engine rankings: the newly created pages are typically filled with links to the hacker's website and use popular or high-traffic keywords to trick search engine algorithms. These pages might appear in the search results, driving unsuspecting traffic towards the hacker's sites.

- Execute Phishing attacks or Malware: users may click on a legitimate-looking link, only to be directed to a page that has been hacked. From there, they could be tricked into giving away sensitive information or downloading malicious software.

## Symptoms of the "Japanese Keyword Hack"?

Victims of the "Japanese Keyword Hack" might notice:
- a sudden drop in website traffic
- an unusual influx of traffic to specific pages filled with unfamiliar content
- a large amount of pages with Japanese caracters on Google Search results

If the website has been linked to the Google Search Console, the website owner will receive email warning alerts.

## Steps to remove the malware from Google Search

**Step 1: Retrieve all indexed pages by Google for your website**

Go to the Search Console and export all URLs.

**Step 2: Create a text file with all URLs you want to remove**

Make sure you verify each URL before including it in this list.
Export this list as a CSV file.

**Step 3: Use a tool to automate the manual process on the Google Search Console**

- Download and unzip the file `google-search-console-bulk-url-removal.zip`
- Go to chrome://extensions/ and turn on "Developer mode"
- Click on "Load unpacked extension" and select the folder `google-search-console-bulk-url-removal`
- Follow the steps to use the plugin

Google has a daily quota of 1000 per day.

If you want to use the last version of the extension, you can download it on [this page](https://github.com/noitcudni/google-search-console-bulk-url-removal).

**Step 4: Wait for Google to process all requests**

After submitting your URLs, Google may take some time to process your request.

## Security Considerations

While this process helps to remove maliciously injected Japanese keywords, it does not address the underlying security vulnerability that allowed the hack to occur.
We recommend conducting a thorough security audit of your website to identify and resolve the root cause of the issue.

## Limitations

This process is specifically designed for the Japanese Keyword Hack. It may not be effective against other forms of SEO spam or hacking attempts. Additionally, it relies on Google Search Console, and therefore can only address URLs that have been indexed by Google.

## Author

This guide was created by Yann Rimbaud [@yrimbaud](https://github.com/yrimbaud/).
