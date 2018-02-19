Here’s a list of resources you might helpful as you begin to ramp up with Alexa skill development.


## Getting Started
1. Your first few skills (in this order):
	1. Your first skill: [Space Facts](https://github.com/alexa/skill-sample-nodejs-fact) - introduces you to Alexa Skills Kit, the basic concepts like intents, utterances, invocation name.
	2. Your second skill: [City Guide](https://github.com/alexa/skill-sample-nodejs-city-guide) - introduces slots (capture input from user), and calling external API to get data (Yahoo Weather)
	3. Your third skill: [Petmatch](https://github.com/alexa/skill-sample-nodejs-petmatch) - Introduces memory persistence (remembering what user said), Entity Resolution (adding synonyms to your slot values.
4. [CodeAcademy: Learn Alexa](https://www.codecademy.com/learn/learn-alexa) - Learn how to build an Alexa Skill from within your browser with this beginner friendly tutorial on CodeAcademy!
      1. Build your first skill (invocation name, intents, utterances)
      2. Create your Lambda function (introduction to AWS Lambda)
      3. Get User Input (slots)
      4. Add Persistence to your skill (DynamoDB)
5. Videos Tutorials/Walkthroughs - [alexa.design/training](https://alexa.design/training)



## Useful Alexa blog posts

## Popular Tutorials & How-to Guides
- [Alexa Voice Design Guide](http://alexa.design/guide)
- [Publishing Your Skill Code to Lambda via the Command Line Interface](https://developer.amazon.com/blogs/post/Tx1UE9W1NQ0GYII/Publishing-Your-Skill-Code-to-Lambda-via-the-Command-Line-Interface)
- [Alexa Account Linking: 5 Steps to Seamlessly Link Your Alexa Skill with Login with Amazon](https://developer.amazon.com/blogs/post/Tx3CX1ETRZZ2NPC/Alexa-Account-Linking-5-Steps-to-Seamlessly-Link-Your-Alexa-Skill-with-Login-wit)
- Alexa CLI: [Getting Started with the Alexa Skill Management API and the Alexa Skills Kit Command-line Interface](https://developer.amazon.com/blogs/alexa/post/71ef5f47-c502-4e3d-8e61-9a6cd38b8e5c/getting-started-with-the-alexa-skill-management-api-and-the-alexa-skills-kit-command-line-interface)
- **Entity Resolution and Synonyms**
	- [Alexa Skill Teardown: Understanding Entity Resolution with the Pet Match Skill](https://developer.amazon.com/blogs/alexa/post/cfbd2f5e-c72f-4b03-8040-8628bbca204c/alexa-skill-teardown-understanding-entity-resolution-with-pet-match)
	- [How to Maintain an Engaging Voice-First Experience Using Third-Party APIs](https://developer.amazon.com/blogs/alexa/post/3a38abcf-00e2-4fc9-8191-6b208474f29c/how-to-maintain-an-engaging-voice-first-experience-using-third-party-apis?mkt_tok=eyJpIjoiTVRSak5XUmxPRGt5TURndyIsInQiOiJhbU9MeExWUXRyRkZWakRMY3d5QVwvRkdSdTJ4Q2dDbFRMWXZiQ2pidFpBUGtcLytIa3lPQ2kxOWp3WVVISUF2d3RXU3Zmc2JITmVCMW1QXC9kdDY5bzN4ZHlkRWpqVDVEeEhtWDc3OFwvYTZMV1pLTDNcL3RXXC9rc3NURFRUN3B2NitPTCJ9)
- **Testing and Automation**
	- [Building Engaging Alexa Skills: Why Testing and Automation Matter](https://developer.amazon.com/blogs/alexa/post/e2f3d18c-13ca-4796-bc83-e8a196f20e57/building-engaging-alexa-skills-why-testing-and-automation-matter?mkt_tok=eyJpIjoiTVRSak5XUmxPRGt5TURndyIsInQiOiJhbU9MeExWUXRyRkZWakRMY3d5QVwvRkdSdTJ4Q2dDbFRMWXZiQ2pidFpBUGtcLytIa3lPQ2kxOWp3WVVISUF2d3RXU3Zmc2JITmVCMW1QXC9kdDY5bzN4ZHlkRWpqVDVEeEhtWDc3OFwvYTZMV1pLTDNcL3RXXC9rc3NURFRUN3B2NitPTCJ9)


## Recent announcements (Feb 2018)

1. **New Alexa Skills Kit Developer Console**: [Blog Post](https://developer.amazon.com/blogs/alexa/post/ea373bd3-cd80-4b09-b243-2b986d2922a0/new-alexa-skills-kit-developer-console-beta-streamlines-development-process?mkt_tok=eyJpIjoiTVRSak5XUmxPRGt5TURndyIsInQiOiJhbU9MeExWUXRyRkZWakRMY3d5QVwvRkdSdTJ4Q2dDbFRMWXZiQ2pidFpBUGtcLytIa3lPQ2kxOWp3WVVISUF2d3RXU3Zmc2JITmVCMW1QXC9kdDY5bzN4ZHlkRWpqVDVEeEhtWDc3OFwvYTZMV1pLTDNcL3RXXC9rc3NURFRUN3B2NitPTCJ9) | [Video Walkthrough](https://www.youtube.com/watch?v=6YwBxpZpRDo&feature=youtu.be)
2. [New AMAZON.SearchQuery Slot](https://developer.amazon.com/blogs/alexa/post/a2716002-0f50-4587-b038-31ce631c0c07/enhance-speech-recognition-of-your-alexa-skills-with-phrase-slots-and-amazon-searchquery?mkt_tok=eyJpIjoiTVRSak5XUmxPRGt5TURndyIsInQiOiJhbU9MeExWUXRyRkZWakRMY3d5QVwvRkdSdTJ4Q2dDbFRMWXZiQ2pidFpBUGtcLytIa3lPQ2kxOWp3WVVISUF2d3RXU3Zmc2JITmVCMW1QXC9kdDY5bzN4ZHlkRWpqVDVEeEhtWDc3OFwvYTZMV1pLTDNcL3RXXC9rc3NURFRUN3B2NitPTCJ9)
3. [AMAZON.YesIntent and AMAZON.NoIntent now compatible with Dialog Management Features](https://developer.amazon.com/blogs/alexa/post/ea90c23d-42e2-46ee-8a2f-0df749030a3b/amazon-yesintent-and-amazon-nointent-now-compatible-with-ask-dialog-management-features?mkt_tok=eyJpIjoiTVRSak5XUmxPRGt5TURndyIsInQiOiJhbU9MeExWUXRyRkZWakRMY3d5QVwvRkdSdTJ4Q2dDbFRMWXZiQ2pidFpBUGtcLytIa3lPQ2kxOWp3WVVISUF2d3RXU3Zmc2JITmVCMW1QXC9kdDY5bzN4ZHlkRWpqVDVEeEhtWDc3OFwvYTZMV1pLTDNcL3RXXC9rc3NURFRUN3B2NitPTCJ9)



- [Voice Design Guide](https://developer.amazon.com/designing-for-voice/) - A great resource for learning conversational and voice user interface design.




## Alexa Skill Templates (with learning objectives)

[Click here](https://github.com/alexa?q=skill-sample) for a complete list of Alexa Templates available on GitHub.

1. [Hello World](https://github.com/alexa/skill-sample-nodejs-hello-world) - "learn":["basics"]
2. [Fact Skill](https://github.com/alexa/skill-sample-nodejs-fact) - "learn":["basics","random"]
3. [City Guide](https://github.com/alexa/skill-sample-nodejs-city-guide) - "learn":["slots","built-in","state management","api","nytimes"]
4. [Pet Match](https://github.com/alexa/skill-sample-nodejs-petmatch) - "learn":["slots","built-in","entity resolution","persistence"]
5. [Quiz Game](https://github.com/alexa/skill-sample-nodejs-quiz-game) - "learn":["custom","slots","built-in","attributes","state management","speechcons","ssml"]
6. [Team Lookup](https://github.com/alexa/skill-sample-nodejs-team-lookup) - "learn":["slots","custom","built-in","state management","attributes","search"]
7. [How to](https://github.com/alexa/skill-sample-nodejs-howto) - "learn":["basics","custom","slots","attributes"]
8. [Trivia](https://github.com/alexa/skill-sample-nodejs-trivia) - "learn":["basics","slots","built-in","state management","attributes"]
9. [High Low Game](https://github.com/alexa/skill-sample-nodejs-highlowgame) - "learn":["slots","built-in","state management","attributes","dynamodb"]
10. [Decision Tree](https://github.com/alexa/skill-sample-nodejs-decision-tree) - "learn":["slots","custom","state management","attributes"]
11. [Calendar Reader](https://github.com/alexa/skill-sample-nodejs-calendar-reader):"learn" - "learn":["slots","built-in","state management","calendar","ics"]
12. [RSS/Atom Feed Reader](https://github.com/alexa/skill-sample-nodejs-feed) - "learn":["slots","built-in","custom","state management","attributes","rss","atom","feeds","dynamodb"]

### Documentation
* [Official Alexa Skills Kit Node.js SDK](https://www.npmjs.com/package/alexa-sdk) - The Official Node.js SDK Documentation
*  [Official Alexa Skills Kit Documentation](https://developer.amazon.com/docs/ask-overviews/build-skills-with-the-alexa-skills-kit.html) - Official Alexa Skills Kit Documentation

## Alexa SDK/Libraries
- **Node.js:** (Official) https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs
- **Python:** (Unofficial) https://github.com/johnwheeler/flask-ask
- **Ruby:** (Unofficial) https://github.com/sjmog/ralyxa

## Tools
1. [Skillinator](https://skillinator.io) - a simple tool designed to help quickly prototype Alexa skills created through the Alexa Skills Kit.
2. https://bespoken.tools/bst
3. https://developer.amazon.com/alexa/agencies-and-tools

## Interesting Datasets

- [World Population API](http://api.population.io)
- [Numbers API](http://numbersapi.com) - An API for interesting facts about numbers
- [REST Countries](https://restcountries.eu) - Get information about countries via a RESTful API


### Community

* [Amazon Developer Forums](https://forums.developer.amazon.com/spaces/165/index.html) - Join the conversation!
* [Hackster.io](https://www.hackster.io/amazon-alexa) - See what others are building with Alexa.
* [Alexa Skills Kit Feature Request](https://alexa.uservoice.com/) - request and vote on features you’d like to see in the developer toolset and services for Alexa.
