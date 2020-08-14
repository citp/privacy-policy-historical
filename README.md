# Princeton-Leuven Longitudinal Privacy Policy Dataset

This repository contains text and metadata extracted from
over 1 million policies of the Princeton-Leuven Longitudinal Privacy Policy Dataset spanning more than 20 years. You can find out more about our methodology and a summary of the data [in our preprint paper](https://privacypolicies.cs.princeton.edu/paper).

## What’s in this repository?
- We provide the Markdown formatted text and HTML sources (in the [`policy_html`](https://github.com/citp/privacy-policy-historical/tree/policy_html) branch) of the privacy policies and associated metadata.
- The privacy policies are committed with a timestamp that reflects Internet Archive’s time-of-crawl.
- Each snapshot of a privacy policy is added in a separate commit, so
that different snapshots of the policies can be easily compared.


## How do I navigate the data?
- Use Github search: Use the search box on the top left to look for a domain, keyword or metadata field that you want to investigate. Make sure you search “In this repository”. Click the Commits link on the results page if you are searching for metadata fields.
- Navigate directly to the document: Privacy policies are stored in 3-layer deep folders, organized by first letters. For example, linux.org's privacy policy is stored in [**`l / li / lin / linux.org.md`**](https://github.com/citp/privacy-policy-historical/blob/master/l/li/lin/linux.org.md)

- History view: If you want to see past versions of a privacy policy, click the history link, while viewing a snapshot of the policy.
- Metadata: You can find metadata about the privacy policy snapshot such as the Alexa rank and original Wayback Machine URL by clicking on the commit link ([example](https://github.com/citp/privacy-policy-historical/commit/49691d0802b320c2be4444afe9113838be05675a)). The metadata is JSON-formatted.
 
 ![Diagram Data](../assets/assets/policy-gh-repo.png?raw=true)
 

This repository is primarily intended for manual investigation of privacy policies. You can download a SQLite database version of this data [from our website](https://privacypolicies.cs.princeton.edu/).

You can clone this repository if you want to do more complex, local searches.

## License
Any contribution we (the authors of the paper) have made is public domain. We make no claims about the licensing of any other content. 

## Acknowledgements
We thank Harshvardhan J. Pandit for his useful comments on the repository.
