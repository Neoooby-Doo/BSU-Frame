<!DOCTYPE html>
<html>
<head><title>Profile Frame with Canvas</title></head>
<body>
<h1>Upload Your Photo</h1>
<input type="file" id="upload" accept="image/*"><br><br>
<canvas id="canvas"></canvas><br><br>
<button id="downloadBtn">Download Result</button>

<script>
const canvas = document.getElementById('canvas');
const ctx = canvas.getContext('2d');
const frameImg = new Image();
frameImg.src = 'frame.png';  // your transparent frame PNG

document.getElementById('upload').onchange = function(e) {
    const file = e.target.files[0];
    if (!file) return;

    const img = new Image();
    img.onload = () => {
        // Set canvas size to frame size or image size
        canvas.width = frameImg.width;
        canvas.height = frameImg.height;

        // Draw user image resized to frame size
        ctx.clearRect(0, 0, canvas.width, canvas.height);
        ctx.drawImage(img, 0, 0, canvas.width, canvas.height);

        // Draw frame on top
        ctx.drawImage(frameImg, 0, 0, canvas.width, canvas.height);
    };

    img.src = URL.createObjectURL(file);
};

document.getElementById('downloadBtn').onclick = function() {
    const link = document.createElement('a');
    link.download = 'profile_with_frame.png';
    link.href = canvas.toDataURL('image/png');
    link.click();
};
</script>
</body>
</html>
