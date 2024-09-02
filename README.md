<!DOCTYPE html>
<html>
<head>
  <title>Global Terrorist Dashboard</title>
</head>
<body>
  <h1>My Dashboard</h1>
  <div id="powerbi-dashboard"></div>

  <script src="https://api.powerbi.com/js/powerbi.js"></script>
  <script>
    powerbi.initialize(document.getElementById('powerbi-dashboard'), {
      type: 'report',
      id: '58883440-25b7-4844-8eea-fcb862cade27',
      embedUrl: 'https://app.powerbi.com/reportEmbed?reportId=58883440-25b7-4844-8eea-fcb862cade27&autoAuth=false&ctid=d8bf7c18-5725-4b9e-b118-13388f52e44e'
    });
  </script>
</body>
</html> 
