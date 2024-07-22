function helloWorldUiApp() {

  var ss = SpreadsheetApp.getActiveSpreadsheet();
  var app = UiApp.createApplication() .setTitle("Bem Vindo!!!!");
  app.add(app.createLabel("Hello World"));

  ss.show(app);
}