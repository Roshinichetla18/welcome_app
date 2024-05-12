document.addEventListener("DOMContentLoaded", function() {
  // Show splash screen
  document.getElementById("splash-screen").style.display = "flex";

  // Simulate loading time (2 seconds)
  setTimeout(function() {
    // Hide splash screen
    document.getElementById("splash-screen").style.display = "none";
    // Show welcome screen
    document.getElementById("welcome-screen").style.display = "flex";
  }, 2000);
});