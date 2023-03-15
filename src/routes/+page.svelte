<script>
  let toDo = [
    "Get out of bed",
    "Make coffee",
    "Read feeds",
    "Have shower",
    "Brush teeth",
    "Get dressed",
    "Leave for work",
    "Get breakfast to go",
  ];
</script>

<h1>Assignment 16</h1>
<ol>
  {#each toDo as toDo}
    <li><strong>{toDo}</strong></li>
  {/each}
</ol>
