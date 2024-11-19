# Terminal UI Society

Welcome to TUIS, the Terminal UI Society - a community passionate about making command line interfaces more accessible, intuitive and fun through Terminal User Interfaces (TUIs)!

## Background thoughts

Let's be honest: anyone who works a lot with the command line knows that it can be both a blessing and a curse. On the one hand, it gives you almost magical powers, on the other hand, sometimes you're just annoyed because you can't find the right command, you've forgotten it, it's too similar to other commands and therefore gets mixed up and and and ...


Especially users who use different unix based systems know the problem only too well.

Just think of simple things like:


**install package:** apt install, brew install, dnf install, pkg install, zypper install - but, apk add, pacman -S


**Remove package:** apt remove, dnf remove, zypper remove - but, apk del, brew uninstall, pkg delete, pacman -Rs


**Firewall rule with ufw:** `ufw allow proto tcp from 192.168.0.4 to any port 22`


**Same rule with firewall-cmd:** `firewall-cmd --permanent --add-rich-rule='rule family=“ipv4” source address=“192.168.0.4” port port=“22” protocol=“tcp” accept'`.


And there are many more examples.
Can the command line be powerful and intuitive at the same time? We think so! That's why we make use of “Terminal User Interfaces” to build a bridge between powerful command lines and user-friendly and resource-saving graphics - making the power of code accessible to all.
 


## Why TUIs?

- **Accessibility**: Lowering the barrier to entry for CLI tools
- **Efficiency**: Combining the power of the CLI with intuitive navigation
- **Aesthetics**: TUIs bring visual appeal to terminal applications
- **Functionality**: TUIs help retain all terminal functionality while adding user-friendly layers.
- **Fun factor**: Plus, TUIs simply make interacting with the terminal more fun and enjoyable

## Our projects

### Current
- **[Diamond](https://github.com/terminal-ui-society/diamond)**: A modular framework for an interactive TUI menu system for common CLI commands. Uses `dialog` as TUI backend.

### Planned
- TUI design guidelines and best practices
- TUI component library
- Tutorials
- Showcases

## Join our cause

We are building a community of developers, designers and enthusiasts who believe in the potential of Terminal User Interfaces. Whether you are:

- A CLI power user
- A TUI developer
- A UX enthusiast
- Someone who wants to make terminals more accessible
- Or just curious about TUIs

There's a place for you here and you're welcome

## How you can contribute

- Test our tools and give us feedback
- Share your ideas for new TUI projects
- Contribute to existing projects
- Create tutorials or documentation
- Help with the translations
- Spread the word about TUIs
- Share your own TUI projects

## Here again, what is important to us:

- **Accessibility**: The terminal should be as accessible as possible for everyone
- **Innovation**: The terminal has its place in an IT ecosystem and its evolution should not come to a standstill.
- **Community**: Users should support each other and learn from each other
- **Open Source**: Sharing knowledge and code freely is a fundamental concept to us
- **User experience**: Focus on the user as the center of terminal interactions

<!--
## Resources

- TUI Development Guide](Link-to-Guide)
- Best Practices](link-to-practices)
- Community projects](link-to-projects)
- Learning materials](link-to-materials)

## 🌐 Connect with us

- Join our [Discord](link-to-discord)
- Follow us on [Twitter](link-to-twitter)
- Visit our [Blog](link-to-blog)
-->

---

> The terminal is not just a tool, but an experience waiting to be improved.

---

Give our repositories a star to help popularize more user-friendly terminal interfaces!

## License

Our projects are typically released under the MIT license to encourage wide adoption and modification.

---

*TUIS - Terminal UI Society - Making the Command Line a Better Place, One TUI at a Time*
