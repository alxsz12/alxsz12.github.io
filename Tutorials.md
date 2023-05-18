---
layout: page
title: Tutorials
---

- [ ] [PROS Tutorial](tutorials/PROS.md)
- [ ] [Okapilib Tutorial]()
- [ ] [PID & Slew Tutorial]()
- [ ] [Lift Pid]()
- [ ] [Inertial Tutorial]()
- [ ] [Odometry Tutorial]()
- [ ] [Pure Pursuit]()
- [ ] [State Machines]()
- [ ] [Sylib Controller Tutorial]()
- [ ] [LVGL Tutorial]()
- [ ] [Auton Selection]()
- [ ] [Pong]()


## Tutorials are in recommended order that you should complete them


###### Check Of The Tutorials You've Completed!


// ------------------------------- 

# Interactive Task List

<ol id="task-list">
  <li><input type="checkbox" id="task1"><label for="task1">Task 1</label></li>
  <li><input type="checkbox" id="task2" checked><label for="task2">Task 2</label></li>
  <li><input type="checkbox" id="task3"><label for="task3">Task 3</label></li>
</ol>

<script>
  const taskList = document.getElementById('task-list');
  const checkboxes = taskList.querySelectorAll('input[type="checkbox"]');

  checkboxes.forEach((checkbox) => {
    checkbox.addEventListener('change', function() {
      const label = this.nextElementSibling;
      if (this.checked) {
        label.classList.add('checked');
      } else {
        label.classList.remove('checked');
      }
    });
  });
</script>

<style>
  .checked {
    text-decoration: line-through;
    color: gray;
  }
</style>

//-----------------
# Interactive Task List

<ol id="task-list">
  <li>
    <input type="checkbox" id="task1">
    <label for="task1">
      <a href="https://example.com/task1">Task 1</a>
    </label>
  </li>
  <li>
    <input type="checkbox" id="task2" checked>
    <label for="task2">
      <a href="https://example.com/task2">Task 2</a>
    </label>
  </li>
  <li>
    <input type="checkbox" id="task3">
    <label for="task3">
      <a href="https://example.com/task3">Task 3</a>
    </label>
  </li>
</ol>

<script>
  const taskList = document.getElementById('task-list');
  const checkboxes = taskList.querySelectorAll('input[type="checkbox"]');

  checkboxes.forEach((checkbox) => {
    checkbox.addEventListener('change', function() {
      const label = this.nextElementSibling;
      if (this.checked) {
        label.classList.add('checked');
      } else {
        label.classList.remove('checked');
      }
    });
  });
</script>

<style>
  .checked {
    text-decoration: line-through;
    color: gray;
  }
</style>

