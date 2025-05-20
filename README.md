onEvent("start", "click", function( ) {
  setScreen("weaponQuestionUno");
  stopSound("01.mp3");
  playSound("sound://category_instrumental/harpe_pluck_1.mp3", false);
});
console.log("begin");
onEvent("bladesOfChaos3Q1", "click", function( ) {
  playSound("sound://category_instrumental/harpe_pluck_1.mp3", false);
  setScreen("q2");
});
onEvent("leviathanQ1", "click", function( ) {
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
  setScreen("youLose");
});
onEvent("olympianQ1", "click", function( ) {
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
  setScreen("youLose");
});
onEvent("knivesOfDestructionQ1", "click", function( ) {
  setScreen("youLose");
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
});
console.log("space");
onEvent("atreusButton", "click", function( ) {
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
  setScreen("youLose");
});
onEvent("baldurButton", "click", function( ) {
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
  setScreen("youLose");
});
onEvent("calliopeButton", "click", function( ) {
  playSound("sound://category_instrumental/harpe_pluck_1.mp3", false);
  setScreen("q3");
});
onEvent("thorButton", "click", function( ) {
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
  setScreen("youLose");
});
console.log("space");
onEvent("nemesisWip", "click", function( ) {
  playSound("sound://category_instrumental/harpe_pluck_1.mp3", false);
  setScreen("winScreen");
});
onEvent("odinClaws", "click", function( ) {
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
  setScreen("youLose");
});
onEvent("hadesClaw", "click", function( ) {
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
  setScreen("youLose");
});
onEvent("nemeanCestus", "click", function( ) {
  playSound("sound://category_instrumental/sax_downscale_2.mp3", false);
  setScreen("youLose");
});
console.log("space");
onEvent("againIfYouDareButton", "click", function( ) {
  setScreen("beginScreen");
  setProperty("kratosMan", "hidden", true);
});
onEvent("goHome", "click", function( ) {
  setScreen("beginScreen");
  setProperty("kratosMan", "hidden", false);
});
