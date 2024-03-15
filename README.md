<!DOCTYPE html>
<html>
  <head>
    <title>Refresh Counter</title>
    <script>
      // Function to increment the counter and update the display
      function incrementCounter() {
        // Get the current counter value from local storage
        var counter = localStorage.getItem("refreshCounter");

        // Check if the counter exists in local storage
        if (counter === null) {
          // If it doesn't exist, set it to 1
          counter = 1;
        } else {
          // If it exists, parse the value and increment it
          counter = parseInt(counter) + 1;
        }

        // Store the updated counter value in local storage
        localStorage.setItem("refreshCounter", counter);

        // Display the counter value on the webpage
        document.getElementById("counter").textContent = counter;
      }
    </script>
  </head>
  <body onload="incrementCounter()">
    <h1>Page Refresh Counter</h1>
    <p>Number of Refreshes: <span id="counter">0</span></p>
  </body>
</html>
## Profile

```python
class Profile:
    def __init__(self):
        self.name = "Martin 马丁"
        self.company = "Development Seed"
        self.role = "Software Engineer"
        self.code = ["PHP", "Javascript", "Python"]
        self.tools = ["Laravel", "Codeigniter", "WordPress"]
        self.use = ["vscode", "pycharm", "NuSphere"]
        self.love = "Coding ..."
        self.dark_mode = False
me = Profile()
