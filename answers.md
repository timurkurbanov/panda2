var image = document.querySelector('.profile-image');
image.src = "https://picsum.photos/200/300"

var left = document.querySelector('#left-image img');
left.src = "https://picsum.photos/300/300"

var h1 = document.querySelector('h1.highlight');
h1.innerHTML = "You";

var h3 = document.querySelector('#employment h3')
h3.innerText = "Something else"

var body = document.body
body.style.backgroundColor = "orange"

var light = document.querySelectorAll('.highlight');
light.forEach(e => {e.style.backgroundColor = 'white'})

var h1 = document.querySelector('h1');
h1.style.fontFamily = 'monospace';

icon = document.querySelectorAll('.action-icon-bg')
icon.forEach(e => {e.style.backgroundColor = 'black'})

input = document.querySelector('#message');
input.placeholder = "Identify Yourself";

input = document.querySelector('.contact-info')
input.placeholder = "state your business"

input = document.querySelector('.contact-info')
input.value = "your nemesis"

input = document.querySelector('#email')
input.value = "koalathebear@gmail.com"

input = document.querySelector('#submit')
input.value = "En garde!"

input = document.querySelector('#submit')
input.disabled = true;

info = document.querySelector('.bio-info');
info.style.display = 'None'