# Distribution & Loading

- There’s a lot of up-front work to be done before you can render a widget on a pub- lisher’s page. First, you’ve got to distribute your script include snippet, the entry point for loading the application. You then need to load any dependencies, like additional JavaScript files, or libraries. Last, you need to pass identifying information from the host page to the application, so that you can properly retrieve and submit data for the correct object.
- You’ve seen how there are a variety of techniques for implementing each of these first steps. They vary in complexity and scope. It’s up to you to choose the techniques that best suit your application.
- At this point, product widget development is well under way. You’ve given your loyal publishers a script include snippet that they’ve since added to their HTML source code. That snippet is loading your initial script file, widget.js, onto their web page. That initial script has loaded all its dependent JavaScript files and libraries. The script has also extracted the product ID from the script include snippet, and used that ID to extract the corresponding product information from the embedded catalog object.
- All this code is executing on the publisher’s page, but there’s nothing to see yet. The widget still hasn’t been rendered. Luckily, this is the focus of the next chapter, “Rendering HTML and CSS.”

### Related

- [[3rd-party-js]]


