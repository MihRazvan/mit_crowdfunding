Inspiration
The inspiration behind my project for the Eth.id challenge was the concept of a modular profile, where a developer iFrame could embed different types of Apps. As a beginner in coding, I was eager to create something that would make use of Smart Contracts and Solidity, as these are areas I am actively working on improving.

What it does
My app, called "Eh.id Crowdfunding App," allows the owner of the .id profile to create a crowdfunding campaign, which others can fund using their Metamask wallet. As the owner of the profile, you can create a campaign with a name, deadline, and funding goal. The campaign ends when the funding goal is reached or when the deadline is reached. Only the owner of the .id profile can withdraw funds, but the campaign will also end if the owner withdraws before the deadline.

How we built it
I started by coding the Smart Contract in Solidity and compiled/deployed it using Thirdweb. The Smart Contract is of low complexity and features functions such as createCampaign, fund, withdraw, and more. For the frontend, I used React.js and accessed the Smart Contract using the ABI and Bytecode with JSON. I made sure to correctly import all the required dependencies, such as web3 and React. I also added CSS to polish the final draft. The last step was deploying my webpage using Netlify and integrating it into the Eth.id developer iFrame.

Challenges we ran into
I spent a significant amount of time deciding on the right approach for a project involving Smart Contracts and settled for creating the project locally and using VSCode. Additionally, I spent considerable time figuring out dependencies and installing different packages in my terminal. I encountered issues with JavaScript in the last four hours of the hackathon, as my app was unable to generate the active campaign page as intended.

Accomplishments that we're proud of
As a freshman student with minimal coding experience, I am proud of the progress I made with my project during this hackathon. This was my first hackathon, and I am thrilled with the learning opportunity it provided me. I gained valuable knowledge on how Solidity works, including contracts, payable functions, ABI and Bytecode, compiling and deploying, working with private keys, and more. I also learned about JavaScript, package.json dependencies, and integrating React.js with Solidity. I also gained experience using tools such as Ganache, testnets like Goerli and Sepolia, Thirdweb, Tailwind CSS, and more.

What's next for Eh.id Crowdfunding App
Moving forward, my plan is to continue working on my project and make it work as intended. I will address the issues I encountered during the hackathon and continue to improve the functionality and usability of the Eh.id Crowdfunding App. I am excited about the potential of my project and look forward to further enhancing it in the future.
