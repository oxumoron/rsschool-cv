<h1 id="profil">Artem Suprun</h1>

<h1 id="contact">My Contact Info:</h1>

<ul>
  <li><strong>Phone: </strong>+380508218868, +4915164065182</li>
  <li><strong>E-mail: </strong> <a href="oxymoron.dr@gmail.com">oxymoron.dr@gmail.com</a></li>
  <li><strong>Github: </strong> <a href="https://github.com/oxumoron/">Oxumoron</a></li>
  <li><strong>Telegram: </strong> <a href="https://t.me/Oxymoron_666">Artem Suprun</a></li>
</ul>

<h1 id="about">About Me</h1>
<p>I love technology and everything connected with it. Now I am developing websites and looking for myself in this direction. I have experience as a system administrator in supporting a small network of 20 users,
installing software, and maintaining office equipment.</p>
<ul>
  <li><strong>My strengths:</strong>
    <ul>
      <li>Quick learner</li>
      <li>Diligence</li>
      <li>Team playing</li>
    </ul>
  </li>
</ul>

<blockquote>
  <p><strong>2b || !2b</strong></p>
</blockquote>

<h1 id="skills">Skills</h1>

<ul>
  <li>HTML</li>
  <li>CSS (Bootstrap, SASS/SCSS, BEM), Materialize CSS</li>
  <li>JavaScript (Fundamentals, ES6+, DOM, JSON, Asynchronous JavaScript)</li>
  <li>Gulp</li>
  <li>jQuery, Node.js, Express.js</li>
  <li>MongoDB</li>
  <li>Git/GitHub</li>
  <li>Figma, Photoshop</li>
</ul>

<h1 id="code-examples">Code Examples</h1>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>const text1 = "The Tao gave birth to machine language. Machine language gave birth to the assembler. The assembler gave birth to the compiler. Now there are ten thousand languages. Each language has its purpose, however humble. Each language expresses the Yin and Yang of software. Each language has its place within the Tao. But do not program in COBOL if you can avoid it.";

let arr =[];
let textAll = "";
let charsArr = [];

const form = document.querySelector(".form");
const textarea = document.querySelector(".textarea");

form.addEventListener("submit", function(event){
event.preventDefault();

textAll = textarea.value;
textAll = textAll.replace(/[^a-zа-яё\s]/gi, '');

alert(findFirstNonRepeatingChar(textAll));

arr =[];
charsArr = [];
});

function findFirstNonRepeatingChar(text){
const splitArr = text.split(" ");

for (const el of splitArr){

    firstNonRepeatingChar(el,charsArr);

};

firstNonRepeatingChar(charsArr,arr);

if(arr.length === 0){

    arr.push("No unique values");

}

return arr;
}

function firstNonRepeatingChar(inputStr,outputArr) {
for (let i = 0; i < inputStr.length; i++) {

    let char = inputStr[i];

    if (inputStr.indexOf(char) === inputStr.lastIndexOf(char)) {

      outputArr.push(char);

      return outputArr;
    }

}
}

</code></pre></div></div>

<h1 id="education">Education</h1>

<ul>
  <li><strong>The eastern ukrainian national university named after v. Dal</strong>
    <ul>
      <li>Informatics</li>
    </ul>
  </li>
  <li><strong>Nix solutions</strong>
    <ul>
      <li><a href="https://www.nixsolutions.com/">Full stack developer course</a></li>
    </ul>
  </li>
</ul>

<h1 id="languages">Languages</h1>

<ul>
  <li><strong>Russian,Ukrainian</strong> - native.</li>
  <li><strong>English</strong> - A2</li>
  <li><strong>German</strong> - A2</li>
</ul>
