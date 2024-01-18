    greetWorld() {
        return "Hello, fellow explorer! 🌍✨";
    }
    console.log("👋 Welcome to the Repository of Curiosity! 🚀 ");



    MyGitHubJourney () {
    constructor() {
        this.username = "Ayush Mandliya ";
        this.email = "ayushmandliya5@gmail.com ";
        this.currentMission = "Conquering the coding cosmos ";
        this.favoriteTechStack = ["JavaScript", "React", "Node.js " ];
        this.programming=[" C, C++, Python" ];
        this.connectOnPlatforms = {
            "LinkedIn": "https://www.linkedin.com/in/ayush-mandliya-226735227 ",
            "Twitter": "https://twitter.com/ayushmandliya5 ",
            "Leetocde": "https://leetcode.com/Ayush_Mandliya/ "
        };
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

