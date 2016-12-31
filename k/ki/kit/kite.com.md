> *The following text is extracted and transformed from the kite.com privacy policy that was archived on 2016-12-31. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20161231231542id_/https%3A//www.kite.com/privacy) for the most accurate reproduction.*

# Kite - Privacy

### What information does Kite access on my computer?

Kite only works in the directories for which you have enabled it.

  1. Kite reads all files named *.py in enabled directories (and any subdirectories).
  2. When you open a Python source file, Kite receives information about each change you make in your editor while that file is open.
  3. When you type commands into the terminal, Kite uses the OS X Accessibility API to read the full terminal buffer. This happens in all working directories. Kite doesn’t read password input where the password is not echoed in the terminal.
  4. Kite reads and writes files in ~/.kite for its own internal use



### What information does Kite send over the network?

In order to show you information about the libraries and APIs you are interacting with, Kite sends some information about the code you are writing to our backend. This includes:

  * Contents of Python files in enabled directories.
  * Per-edit information when you are typing into a Python source file.
  * The current and previous terminal command, and the output from the previous command.



### How does Kite secure this network traffic?

As you would expect, all traffic goes over https.

### What information does Kite keep around on its servers?

  * Usage information about which results you click on in the sidebar.
  * Contents of all Python files in enabled directories.
  * Information about each edit that you make within any Python file in an enabled directory.
  * All terminal commands.



Once again, this information is only collected for directories for which you explicitly enable Kite.

### Why does Kite send information over the network?

Our backend contains an index of tens of thousands of python libraries, including documentation, examples, and models of how public-domain code uses these libraries. This index is simply too large to ship to each client.

One of Kite’s goals is to bring all the programming information available on the internet to your development workflow. It turns out that the internet contains a _lot_ of information about programming, so Kite is architected as a cloud service. The up side is: the internet contains a _lot_ of information about programming, so Kite can give you some incredibly helpful information.

### Why should I trust Kite?

Many developers have already chosen to trust their code to services such as Github and Bitbucket. Furthermore, many of us already implicitly trust some of our deepest secrets to chat apps such as Slack. If you use any of these services or any like them, it is probably because they have earned your trust over time through transparency, product quality, and well-considered privacy policies. At Kite we understand that trust is built over years but can be destroyed in a moment. We plan to earn your trust the hard way, starting with writing this page.

### Does Kite offer an on-premise option?

Kite does not have an on-premise offering at the moment. If you are interested in an on-premise or AWS co-managed installation of Kite servers, please email [onprem@kite.com](mailto:onprem@kite.com).
