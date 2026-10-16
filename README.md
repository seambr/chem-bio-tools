function showPoint(x, y) {
  annotations.set("h1", (ctx) => {
    ctx.fillStyle = "yellow";
    ctx.beginPath();
    ctx.arc(x, y, 5, 0, 2 * Math.PI);
    ctx.fill();
  });
}

showPoint(200, 150);
annotations.remove("h1");
