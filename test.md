# JS Test

Enter two words:

<input id="input1" placeholder="First word">
<input id="input2" placeholder="Second word">
<button onclick="combineText()">Combine</button>

<p id="result"></p>

<script data-exec-on-render>
  function combineText() {
    const a = document.getElementById('input1').value;
    const b = document.getElementById('input2').value;
    document.getElementById('result').innerText = a + ' ' + b;
  }
</script>
