<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Đề thi tương tác - AI và Ma trận nghịch đảo</title>

<!-- MathJax -->
<script>
window.MathJax = {
  tex: {
    inlineMath: [['\\(','\\)'], ['$', '$']]
  }
};
</script>

<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<style>
    *{
        box-sizing:border-box;
    }

    body{
        margin:0;
        padding:20px;
        font-family:Arial, sans-serif;
        background:#f2f6fb;
        color:#222;
    }

    h1{
        text-align:center;
        color:#0056a6;
    }

    h2{
        color:#0d4f8b;
        margin-top:40px;
    }

    .intro{
        background:white;
        padding:20px;
        border-radius:12px;
        margin-bottom:25px;
        box-shadow:0 0 10px rgba(0,0,0,0.08);
    }

    .question{
        background:white;
        border-radius:12px;
        padding:20px;
        margin-bottom:20px;
        box-shadow:0 0 8px rgba(0,0,0,0.08);
    }

    .question h3{
        margin-top:0;
        color:#004080;
    }

    .option{
        border:2px solid #d6d6d6;
        border-radius:10px;
        padding:12px;
        margin-top:10px;
        cursor:pointer;
        transition:0.2s;
    }

    .option:hover{
        background:#eef6ff;
    }

    .correct{
        background:#c8ffd2 !important;
        border-color:#22aa44 !important;
    }

    .wrong{
        background:#ffd1d1 !important;
        border-color:#cc2222 !important;
    }

    .disabled{
        pointer-events:none;
    }

    .answer-box{
        margin-top:15px;
        padding:15px;
        border-left:5px solid #0077cc;
        background:#f4faff;
        display:none;
        border-radius:8px;
    }

    .tip{
        margin-top:10px;
        background:#fff8d6;
        padding:10px;
        border-radius:8px;
        border-left:5px solid orange;
    }

    .score-board{
        position:sticky;
        top:10px;
        background:#004080;
        color:white;
        padding:15px;
        border-radius:12px;
        margin-bottom:20px;
        text-align:center;
        font-size:20px;
        z-index:999;
    }

    button{
        background:#0056a6;
        color:white;
        border:none;
        padding:12px 20px;
        border-radius:10px;
        cursor:pointer;
        font-size:16px;
        margin-top:20px;
    }

    button:hover{
        background:#003f7a;
    }

    .download{
        text-align:center;
        margin-top:40px;
    }
</style>
</head>

<body>

<h1>ĐỀ THI TƯƠNG TÁC<br>AI & MA TRẬN NGHỊCH ĐẢO</h1>

<div class="score-board">
    Điểm hiện tại: <span id="score">0</span> / 20
</div>

<div class="intro">
    <b>Cấu trúc đề:</b>
    <ul>
        <li>5 câu lý thuyết</li>
        <li>5 câu dễ</li>
        <li>5 câu trung bình</li>
        <li>5 câu khó</li>
    </ul>

    <b>Hướng dẫn:</b>
    <ul>
        <li>Chọn 1 đáp án đúng.</li>
        <li>Đúng → hiện màu xanh.</li>
        <li>Sai → hiện màu đỏ và hiển thị đáp án đúng.</li>
        <li>Có lời giải + mẹo làm nhanh.</li>
    </ul>
</div>

<div id="quiz"></div>

<div class="download">
    <button onclick="downloadHTML()">⬇ Download File HTML</button>
</div>

<script>

const questions = [

/* =========================
   5 CÂU LÝ THUYẾT
========================= */

{
type:"Lý thuyết",
question:"Ba trụ cột sử dụng AI theo bài giảng là gì?",
options:[
"Prompt - Context - Harnessing",
"AI - Machine Learning - Deep Learning",
"Input - Output - Process",
"Claude - Gemini - ChatGPT"
],
correct:0,
explanation:"Ba trụ cột gồm Prompt (ra lệnh), Context (ngữ cảnh), Harnessing (ghì cương AI).",
tip:"Nhớ theo thứ tự: hỏi gì → cung cấp ngữ cảnh → điều khiển đầu ra."
},

{
type:"Lý thuyết",
question:"Vai trò chính của người thầy trong thời đại AI là gì?",
options:[
"Đọc slide PowerPoint",
"Chỉ cách học và điều khiển AI",
"Chép bài cho học sinh",
"Không còn cần thiết"
],
correct:1,
explanation:"Theo bài giảng, người thầy không còn chỉ giảng bài mà hướng dẫn cách học và harnessing AI.",
tip:"Từ khóa: 'Thầy không dạy — thầy chỉ cách'."
},

{
type:"Lý thuyết",
question:"Harnessing có nghĩa gần đúng nhất là gì?",
options:[
"Tắt AI",
"Ghì cương AI",
"Huấn luyện mạng neural",
"Viết code"
],
correct:1,
explanation:"Harnessing được ví như ghì cương con ngựa để AI đi đúng hướng.",
tip:"Nhớ hình ảnh cưỡi ngựa trong bài giảng."
},

{
type:"Lý thuyết",
question:"Minor \\(M_{ij}\\) là gì?",
options:[
"Định thức ma trận ban đầu",
"Định thức sau khi bỏ hàng i cột j",
"Ma trận chuyển vị",
"Định thức nghịch đảo"
],
correct:1,
explanation:"Minor là định thức của ma trận con khi bỏ hàng i và cột j.",
tip:"Minor = ma trận nhỏ hơn."
},

{
type:"Lý thuyết",
question:"Công thức đúng của ma trận nghịch đảo là:",
options:[
"\\(A^{-1}=det(A)adj(A)\\)",
"\\(A^{-1}=\\frac{1}{det(A)}adj(A)\\)",
"\\(A^{-1}=A^T\\)",
"\\(A^{-1}=A^2\\)"
],
correct:1,
explanation:"Đây là công thức chuẩn để tính ma trận nghịch đảo.",
tip:"Luôn nhớ có phân số \\(\\frac{1}{det(A)}\\)."
},

/* =========================
   5 CÂU DỄ
========================= */

{
type:"Dễ",
question:"Tính \\(det\\left(\\begin{pmatrix}2&1\\\\1&3\\end{pmatrix}\\right)\\)",
options:["5","6","4","7"],
correct:0,
explanation:"\\(det(A)=2\\times3-1\\times1=5\\)",
tip:"Ma trận 2x2: ad - bc."
},

{
type:"Dễ",
question:"Nếu \\(det(A)=0\\) thì:",
options:[
"A khả nghịch",
"A không khả nghịch",
"A luôn đối xứng",
"A luôn trực giao"
],
correct:1,
explanation:"Định thức bằng 0 thì không tồn tại nghịch đảo.",
tip:"Không chia được cho 0."
},

{
type:"Dễ",
question:"Ma trận đơn vị ký hiệu là:",
options:["A","B","I","E"],
correct:2,
explanation:"Ma trận đơn vị được ký hiệu là I.",
tip:"I = Identity."
},

{
type:"Dễ",
question:"\\(C_{ij}=\\ ?\\)",
options:[
"\\((-1)^{i+j}M_{ij}\\)",
"\\(M_{ij}+1\\)",
"\\(det(A)\\)",
"\\(A^T\\)"
],
correct:0,
explanation:"Đây là công thức cofactor.",
tip:"Nhớ dấu \\((-1)^{i+j}\\)."
},

{
type:"Dễ",
question:"Adjugate là:",
options:[
"Ma trận nghịch đảo",
"Ma trận chuyển vị của cofactor",
"Minor",
"Định thức"
],
correct:1,
explanation:"Adj(A) là chuyển vị của ma trận cofactor.",
tip:"Adj = transpose của cofactor."
},

/* =========================
   5 CÂU TRUNG BÌNH
========================= */

{
type:"Trung bình",
question:"Tính nghịch đảo của \\(\\begin{pmatrix}1&0\\\\0&1\\end{pmatrix}\\)",
options:[
"Chính nó",
"Không tồn tại",
"Ma trận 0",
"\\(2I\\)"
],
correct:0,
explanation:"Ma trận đơn vị nghịch đảo bằng chính nó.",
tip:"I nhân với gì cũng ra chính nó."
},

{
type:"Trung bình",
question:"\\(det\\left(\\begin{pmatrix}4&2\\\\1&3\\end{pmatrix}\\right)= ?\\)",
options:["10","12","8","6"],
correct:0,
explanation:"\\(4\\times3-2\\times1=10\\)",
tip:"Nhân chéo rồi trừ."
},

{
type:"Trung bình",
question:"Nghịch đảo của \\(\\begin{pmatrix}1&2\\\\3&4\\end{pmatrix}\\) có phần tử góc trên trái là:",
options:["-2","2","4","1"],
correct:0,
explanation:"\\(A^{-1}=\\frac{1}{-2}\\begin{pmatrix}4&-2\\\\-3&1\\end{pmatrix}\\Rightarrow -2\\)",
tip:"Đổi vị trí a,d rồi đổi dấu b,c."
},

{
type:"Trung bình",
question:"Nếu \\(A A^{-1}=I\\), thì \\(A^{-1}A=?\\)",
options:["0","A","I","Không xác định"],
correct:2,
explanation:"Tính chất ma trận nghịch đảo.",
tip:"Nghịch đảo hai phía đều ra I."
},

{
type:"Trung bình",
question:"AI clone giáo viên nhằm:",
options:[
"Thay thế hoàn toàn giáo viên",
"Nhân bản phong cách giảng dạy",
"Loại bỏ học sinh",
"Tăng bài tập"
],
correct:1,
explanation:"AI giúp nhân bản phong cách dạy học.",
tip:"Từ khóa: clone phong cách."
},

/* =========================
   5 CÂU KHÓ
========================= */

{
type:"Khó",
question:"Tính \\(det\\left(\\begin{pmatrix}2&3\\\\5&7\\end{pmatrix}\\right)\\)",
options:["-1","1","29","14"],
correct:0,
explanation:"\\(2\\times7-3\\times5=14-15=-1\\)",
tip:"Cẩn thận dấu âm."
},

{
type:"Khó",
question:"Nếu \\(det(A)=5\\), thì \\(det(A^{-1})=?\\)",
options:["5","1/5","25","0"],
correct:1,
explanation:"\\(det(A^{-1})=\\frac1{det(A)}\\)",
tip:"Nghịch đảo → lấy nghịch đảo định thức."
},

{
type:"Khó",
question:"Cho \\(A=\\begin{pmatrix}2&1\\\\1&1\\end{pmatrix}\\). Giá trị của \\(A^{-1}\\) là:",
options:[
"\\(\\begin{pmatrix}1&-1\\\\-1&2\\end{pmatrix}\\)",
"\\(\\begin{pmatrix}2&-1\\\\-1&1\\end{pmatrix}\\)",
"\\(\\begin{pmatrix}1&1\\\\1&2\\end{pmatrix}\\)",
"Không tồn tại"
],
correct:0,
explanation:"det=1 nên nghịch đảo chính là ma trận đổi vị trí và đổi dấu.",
tip:"Nếu det=1 thì rất nhanh."
},

{
type:"Khó",
question:"Nếu \\(A^{-1}=A\\), ma trận đó gọi gần đúng là:",
options:[
"Ma trận tự nghịch đảo",
"Ma trận zero",
"Ma trận singular",
"Ma trận ngẫu nhiên"
],
correct:0,
explanation:"A nhân chính nó bằng I.",
tip:"Tự inverse."
},

{
type:"Khó",
question:"Theo bài giảng, điều quan trọng nhất AI chưa thay thế được hoàn toàn là:",
options:[
"Tốc độ tính toán",
"Khả năng ghi nhớ",
"Tư duy định hướng và cảm xúc sư phạm",
"Khả năng lưu file"
],
correct:2,
explanation:"AI mạnh nhưng vẫn cần người thầy định hướng và truyền tư duy.",
tip:"Bài giảng nhấn mạnh 'học tư duy'."
}

];

const quiz = document.getElementById("quiz");
let score = 0;

questions.forEach((q,index)=>{

    const div = document.createElement("div");
    div.className = "question";

    let html = `
        <h3>Câu ${index+1} (${q.type})</h3>
        <p>${q.question}</p>
    `;

    q.options.forEach((opt,i)=>{
        html += `
            <div class="option" onclick="checkAnswer(this, ${i}, ${q.correct}, ${index})">
                ${String.fromCharCode(65+i)}. ${opt}
            </div>
        `;
    });

    html += `
        <div class="answer-box" id="answer-${index}">
            <b>Đáp án đúng:</b> ${String.fromCharCode(65+q.correct)} <br><br>
            <b>Giải thích:</b> ${q.explanation}
            <div class="tip">
                💡 <b>Mẹo làm nhanh:</b> ${q.tip}
            </div>
        </div>
    `;

    div.innerHTML = html;
    quiz.appendChild(div);

});

function checkAnswer(el, selected, correct, index){

    const parent = el.parentElement;
    const options = parent.querySelectorAll(".option");

    options.forEach(op=>op.classList.add("disabled"));

    if(selected===correct){
        el.classList.add("correct");
        score++;
        document.getElementById("score").innerText = score;
    }else{
        el.classList.add("wrong");
        options[correct].classList.add("correct");
    }

    document.getElementById("answer-"+index).style.display="block";

    MathJax.typeset();
}

function downloadHTML(){

    const content = document.documentElement.outerHTML;

    const blob = new Blob([content], {type:"text/html"});
    const a = document.createElement("a");

    a.href = URL.createObjectURL(blob);
    a.download = "de_thi_AI_ma_tran.html";

    a.click();
}

</script>

</body>
</html>
