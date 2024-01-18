console.log("👋 Welcome to the Repository of Curiosity! 🚀 \n");

<img align="right" alt="coder" width="400" src="https://t3.ftcdn.net/jpg/03/18/60/62/360_F_318606217_Hk8jo2MVoI33SQOkYrfOF929J7JgIP0P.jpg">

class MyGitHubJourney {
    constructor() {
        this.username = "Ayush Mandliya \n";
        this.email = "ayushmandliya5@gmail.com \n";
        this.currentMission = "Conquering the coding cosmos \n";
        this.favoriteTechStack = ["JavaScript", "React", "Node.js \n" ];
        this.programming=[" C, C++, Python" \n];
        this.connectOnPlatforms = {
            "LinkedIn": "https://www.linkedin.com/in/ayush-mandliya-226735227 \n",
            "Twitter": "https://twitter.com/ayushmandliya5 \n",
            "Leetocde": "https://leetcode.com/Ayush_Mandliya/ \n"
        };
    }

    greetWorld() {
        return "Hello, fellow explorer! 🌍✨";
    }

    shareExperience() {
        return "Embarking on an epic journey through code. Join me in the quest for knowledge and innovation!";
    }

    getContactInfo() {
        let contactInfo = `📧 Connect with me via email: ${this.email}\n🔗 Find me on:`;
        for (const [platform, link] of Object.entries(this.connectOnPlatforms)) {
            contactInfo += `\n   - [${platform}](${link})`;
        }
        return contactInfo;
    }
}

const adventurer = new MyGitHubJourney();
console.log(adventurer.greetWorld());
console.log(adventurer.shareExperience());
console.log(adventurer.getContactInfo());

