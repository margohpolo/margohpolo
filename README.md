### Hi There :wave:
<br />
Thanks for stopping by.
<br />
<br />
As a hands-on learner, I sometimes tinker/build when I have the time.
<br />
<br />
These are some of the projects I've worked on previously:
<br />
<br />
<details>
<summary>C#/.NET</summary>
<br />
<details>
<summary>Strong Typing with Value Objects</summary>
<br />
Some exploration into Strong Typing in C#.
<br />
<br />
Calculations, with Custom Operators - <a href="http://repo.margohpolo.com/margohpolo/IncomeTaxCalculatorPOC" target="_blank">here</a>.
<br />
<br />
Also explored EF mappings of strong types - <a href="http://repo.margohpolo.com/margohpolo/PropertyTaxCalculator" target="_blank">here</a>.
<br />
<br />
Will be returning to this, perhaps to build a website that'll be useful for people (.NET 8 Blazor...?)
</details>
<br />
<details>
<summary><a href="https://github.com/margohpolo/USBPOC" target="_blank">USB</a></summary>
<br />
Explored a couple of different ways to get details on connected USB devices, including via a PowerShell instance.
<br />
Also built XML documentation of code.
</details>
<br />
<details>
<summary><a href="https://github.com/margohpolo/WebSot" target="_blank">"Project WebSot"</a></summary>
<br />
 A quick build to understand WebSockets across 2 of the more popular WebSocket Libraries, namely <a href="https://github.com/statianzo/Fleck" target="_blank">Fleck</a> for the Server and <a href="https://github.com/sta/websocket-sharp" target="_blank">WebSocket-Sharp</a> for the Console Client.
<br />
<br />
 In hindsight, could've chosen a better Client Library for better feature support, e.g. custom HTTP Headers.
</details>
<br />
<details>
<summary><a href="https://github.com/margohpolo/wwimporters/tree/master" target="_blank">"Project WWImporters"</a></summary>
<br />
Some exploration into Clean Architecture and EFCore started here.
<br />
<br />
Features:
 <ul>
    <li>Reverse-scaffolded the Microsoft example WideWorldImporters DB.</li>
    <li>Added ability to run SQL Scripts (including StoredProcedures) after EF Migrations.</li>
    <li>Added Unit Tests to strictly enforce Clean Architecture at a high level.</li>
 </ul>
<br />
Other Notes:
<ul>
    <li>SystemConfig Tables can be seeded with default values OnCreate.</li>
    <li>History Table handling approach pending.</li>
    <li>Data archiving approach pending.</li>
    <li>"Disposable" DB containers can be introduced for Integration Unit Testing - apparently it's common for Azure projects.</li>
    <li>Noted that the original design still had primitive obsession to be resolved.</li>
</ul>
</details>
<br />
<details>
<summary><a href="https://github.com/margohpolo/DataPOC/tree/main" target="_blank">DataPOC</a></summary>
<br />
 A quick POC Solution for generating Documentation of DB Schema. Supports MarkDown, JSON as well as Excel outputs. While MarkDown and Excel were chosen as the default human-readable options, JSON was included in the scope for future extensibility to support Azure Data Factory mappings.
<br />
<br />
One possible practical use of this Project is to be a Nuget Package that, upon pipeline build, sends the blobs (or streams of bytes?) to update Wikis and other documentation. 
</details>
<br />
<br />
</details>
<br />
<details>
<summary>React/JavaScript</summary>
<br />
<details>
<summary><a href="https://github.com/margohpolo/Countdown" target="_blank">Countdown Timer</a></summary>
<br />
Inspired by several brilliant Frontend Developers on my team, I decided to tinker a little with React and JavaScript.
<br />
<br />
A preference for going with custom SVGs instead of using D3 is still held; intending to revisit this when it's time for more Frontend/JavaScript practical sessions. 
</details>
</details>

<br />
This is what I'm currently working on:
<br />
<br />
<details>
<summary>[C#] <a href="https://github.com/margohpolo/TicTacToeDotNet" target="_blank"> TicTacToeDotNet</a></summary>
<br />
 A code refactoring exercise; pushing the limits of what can be learnt from just 100 lines of smelly code.
 <br />
<br />
 Did take the opportunity to set up a local instance of SonarQube; seeme like SonarQube doesn't capture design pattern smells by default, only the glaringly obvious code smells. Then again, it would be a stretch to expect even ChatGPT to review design patterns well, at least at this point in time.
 <br />
<br />
 This Repo will be updated once it's good to go.
</details>
<br />
