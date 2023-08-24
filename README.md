
var links = [
    "https://i.imgur.com/GMJmUWK.mp4",
    "https://i.imgur.com/WYmJvIL.mp4"
];

function getRandomLink() {
    var randomIndex = Math.floor(Math.random() * links.length);
    return links[randomIndex];
}
