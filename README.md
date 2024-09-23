<div id="statusFrame" style="border: 1px solid black; width: 100px; height: 50px; display: flex; justify-content: center; align-items: center; cursor: pointer;">
    AFK
</div>
<p id="userName">اسم المستخدم</p>

document.getElementById("statusFrame").addEventListener("click", function() {
    document.getElementById("userName").innerHTML += " (غير متصل)";
});
