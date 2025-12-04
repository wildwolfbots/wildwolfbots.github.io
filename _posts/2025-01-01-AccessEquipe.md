---
layout: single
title: "Área para membros"
date: 2025-01-01
---
## Área apenas para membros
<script>
function checkPassword() {
  const input = document.getElementById("pw").value;
  const correct = atob("d2lsZHdvbGZib3Rz");

  if (input === correct) {
    window.location.href = '/secret/members'
  } else {
    alert("Wrong password!");
  }
}
</script>
Senha:
<input type="password" id="pw" placeholder="Senha" onenter="checkPassword()">
<button onclick="checkPassword()">Ok</button>