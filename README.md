# Any Chat Project

Real-time application that allows users to message each other.

![Any Chat Project preview image](https://github.com/elise-bigdevsoon/big-dev-soon-any-chat/blob/main/project-preview.png?raw=true)

## Hello to [BigDevSoon](https://bigdevsoon.me/) 👋

Create code that matters! 🤩

Level up your coding skills by building real-world projects with professional designs.

## Project brief

Dive into the realm of **Any Chat**, a real-time messaging platform that connects users in an instant digital conversation. With intuitive onboarding, this application offers a smooth and interactive chat experience, merging traditional chat dynamics with contemporary design and functionality.

### What you will learn

- **Real-time Server Integration**: Navigate the intricacies of setting up a Node.js server, using technologies like socket.io and express.js. Understand the complexities of managing real-time data flow between frontend and backend.

- **Intuitive UI/UX Design**: Start with an engaging onboarding process and transition through user validation and chat initiation. Master the art of presenting information attractively, catering to both new and returning users.

- **Dynamic Chat Features**: From displaying online user counts to incorporating emoji libraries and managing chat messages, gain firsthand experience in developing features that enhance user engagement and communication.

- **Error Handling**: Ensure the app's resilience by handling user actions like browser refreshes, chat disconnections, or new connections. Grasp the significance of a seamless experience even in unexpected scenarios.

### Requirements

- Create an onboarding page that includes a logo, a title, and a "Get Started" button. The page should feature a split-view layout with two columns. The right column should have a different background and display an image of a hand holding a phone.
- Navigate the user to a centered page with the logo after clicking the "Get Started" button. On this page, users should be able to enter a nickname for the chat. The nickname should be validated to ensure it is between 4 and 60 characters in length. The "Join Chat" button should only be clickable when the nickname is properly validated. Clicking the button should move the user to the main chat page.
- Set up a simple Node.js server using this [tutorial](https://socket.io/get-started/chat). Integrate the server with both the frontend and backend using socket.io and express.js. Keep track of connected users in an array and messages in an array of objects.
- Enhance the main chat page with a header that displays the logo and the number of online users. Retrieve this information from the connected user's array on the Node.js server.
- Create a chat window as the main content of the main chat page. The chat window should occupy most of the page and display messages from top to bottom. Implement scrolling when the messages exceed the height of the chat window. For now, you can mock the messages.
- Add a footer section to the main chat page. The footer should include an emoji icon on the left, a text input with a placeholder of "Send a message...", and a disabled send icon.
- Allow users to send messages by enabling the send icon when at least one character is entered in the text input. Limit the message length to a maximum of 1000 characters (or more). After sending a message, display its content, the nickname (displayed as "You" for the sender or the user's nickname for others), the date in the format "hh:mm", and the position of the message (your messages on the right, other user messages on the left). Store the messages on the Node.js server and render them in the chat window from top (oldest) to bottom (newest).
- Integrate an external library to add emoji support, allowing users to incorporate emojis into their messages by clicking the emoji icon.
- When a user connects or disconnects, send a system message in the middle of the chat. Merge these system messages with other messages based on the sending date and time. Update the online user counter in the header accordingly.
- Handle edge cases when users refresh the browser to ensure they are redirected to the appropriate page based on their connection status (main chat page when connected, onboarding page when disconnected, or connecting for the first time). Improve the overall user experience and user interface of the chat application. Additionally, ensure all other edge cases are handled properly.

## Project assets

Each project comes with additional assets to aid your implementation:

**Starter Files**: Get started with project templates, assets, and resources to kickstart your development process. Simple HTML/CSS/JS files are included.

**Project images**: Access a collection of a few chosen preview project images that can be used to enhance your project.

**Unique Screenshots**: Most cards in the project come with unique screenshots that provide visual guidance for your project's design and requirements.

Additionally, you have the option to download the comprehensive Figma Design for 3 BigTokens. This design includes all visual states and a robust Design System to ensure consistency and precision in your implementation. The "Download Figma design" button is available whenever you choose to elevate your project experience.

## Get started

1. Click the "Start Project" button on the project's page in our app to begin your project.
2. Explore the available project assets, including images, starter files, and unique card screenshots to understand the project's scope.
3. For a comprehensive project experience, download the Figma design for 3 BigTokens.
4. Configure your "Coding setup" using Glitch or GitHub if desired.
5. Dive into the project details through the cards for a deeper understanding.
6. Start coding using your preferred technologies.
7. Refer to the documentation or ask for assistance if needed.
8. Submit your solution, let it shine, and share it with other folks!

## Implementation

Embrace the freedom of choice in your implementation. Whether you're using familiar tools or experimenting with new ones, make this project uniquely yours. Use any combination of languages, libraries, or frameworks as you desire. Push boundaries, learn, and make something to be proud of. 😊

**Setup & Environment**: You can use both [Glitch](https://glitch.com/), a cloud-based editor perfect for quick starts and live previews, or [GitHub](https://github.com/) to lay the groundwork. [GitHub](https://github.com/) is an excellent choice for those building a portfolio or keen on mastering Git. If you're new to coding, consider beginning with [Glitch](https://glitch.com/) to bypass the initial Git learning curve.

No matter your platform choice, feel free to overwrite repository files to suit your project structure. We've included a set of starter files and an `assets` folder, extracted from the design, to streamline your setup process.

**Structuring your project**: Whether you're pacing yourself with Freerun's card-by-card approach or diving into the deep end with Speedrun, it's essential to segment your work. Break down the project into smaller components or sections and plan the implementation based on the provided designs.

### Getting help when stuck

**Community**: Reach out to our "Community questions" section in the project for support. Remember, connecting your Discord account grants you 1 BigToken on your first connection!

**ChatGPT**: For intricate, technical concerns, the "ChatGPT" section in the project is at your disposal. A BIG subscription is required to access this feature.

## Review

Before finalizing your project, take a moment to review your work. This process ensures the quality of your code and fosters self-growth:

1. **Self-Review**: Start by examining your own code. Use this time for introspection, checking that you've adhered to the project's goals and requirements.

2. **Community review**: If you're looking for external opinions, our community is a great place to turn. Fellow developers can offer fresh perspectives, pointing out areas for refinement.

3. **ChatGPT review**: Alternatively, if you're after technical insights, the "ChatGPT" section in the project offers in-depth analysis. This AI-powered tool pinpoints areas of improvement and helps to elevate your code quality.

## Guidelines

1. **Project Planning**: Start by reviewing the design and requirements. Get a good grasp of the project's scope. This foresight can save you time and rework later on.

2. **Design Fidelity**: Strive for a close match with the design. However, creative variations are welcome, especially if they enhance UX/UI. Tools like [PixelParallel](https://chrome.google.com/webstore/detail/pixelparallel-by-htmlburg/iffnoibnepbcloaaagchjonfplimpkob?hl=en) can assist in ensuring design accuracy.

3. **Code Quality**: Ensure your code is clean and efficient. Extensions like [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint), for [VSCode](https://code.visualstudio.com/) users, are invaluable. For beginners, platforms like [Glitch](https://glitch.com/) simplify the coding journey.

4. **Tech Stack Choices**: Choose the right technologies that align with the project's needs. Whether it's a particular framework, library, or platform, your choice can impact the project's flexibility, scalability, and efficiency.

5. **Version Control**: While optional, version control systems like Git can be beneficial, especially for larger projects. If you're keen, delve into [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow), but simplicity is fine for newcomers or straightforward projects.

6. **Testing & Quality Assurance**: Prioritize testing to ensure your project runs seamlessly. Conduct both automated tests, using tools like [Jest](https://jestjs.io/), and manual tests to navigate the application as a user would. Vigilance in identifying and rectifying bugs will lead to a more robust and trustworthy final product.

Ultimately, the beauty of this project lies in the journey and the learning. Use tools that make your workflow efficient and add your unique touch to the design. 💡

## Submit solution

Whether you've just begun or are wrapping up, you have the flexibility to submit your project at any stage via the "Submit solution" button. This not only allows for iterative improvements but also offers a chance to garner feedback early on, making your learning more effective.

Here's a quick guide to ensure a smooth submission:

1. **Cloud-Based Editors**: If you're using cloud-based platforms like [Glitch](https://glitch.com/) or [Replit](https://replit.com/), submission is straightforward. These platforms automatically provide you with both code and preview links.

2. **Manual Deployment**: For those who've built projects on local environments or prefer platforms that require manual deployment, consider services like [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [GitHub Pages](https://pages.github.com/).

3. **Tag Check**: Ensure the `<bds />` tag is present in your `index.html`. This is a crucial step as we'll verify its presence during submission.

4. **Optional Feedback via Discord**: If you've connected your Discord account within our app, you can optionally request feedback during submission. This will initiate a thread on Discord where community members can provide insights. Each thread includes key links such as your repository and preview URL, making it easier for peers to review and comment.

Remember, the aim is not just to finish but to learn and grow. Iterative submissions and community feedback can greatly amplify your learning experience. Best of luck with your project journey!

## Share solution

Celebrating and sharing your accomplishments is a great way to both reinforce your learning and inspire others. Here's how you can do it:

1. **Your Solution**: Once you've submitted your solution, it becomes a part of your portfolio. Share your unique solution link directly from your solution page or use our "Share solution" widget. There, you'll find various social platform buttons to help spread the word effortlessly.

2. **Project Page**: Loved the project? Share the [Any Chat](https://app.bigdevsoon.me/projects/any-chat) with your network. It’s a great way to challenge others and see what they can build.

3. **Invite Friends**: Excited about our platform? Spread the joy! Every time you invite a friend using your unique link found in the Profile or Settings section of our app, and they register, you earn 1 BigToken. Sharing truly is rewarding!

4. **Technical write-up**: Documenting your journey and the technical decisions you made can be an enriching experience. Platforms like [dev.to](https://dev.to/), [HackerNoon](https://hackernoon.com/), and [Medium](http://medium.com/) are excellent places to pen down your thoughts. Not only does it help build your online presence, but it also solidifies your understanding.

5. **Create Free Content**: Making tutorials or content around how you tackled the project can be both fun and educational. Linking back to the project can also drive curiosity and potentially help others in their coding journey.

Remember, every project has a story. Sharing yours might inspire someone else to begin their own. Keep coding, and keep sharing! 🌟

Happy coding! 🚀
