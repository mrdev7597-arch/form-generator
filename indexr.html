<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>एडमिन पैनल - ग्राहक विवरण</title>
<style>
  body{font-family: Arial,sans-serif; padding: 20px; background:#fff8fb;}
  h1{text-align:center; color:#e79ecf; margin-bottom:20px;}
  table{width:100%; border-collapse: collapse; background:#fceaf3; border-radius: 8px;}
  th,td{border:1px solid #f1c4dc; padding:8px; text-align:left;}
  th{background-color:#f9d5e5; color:#bb7dbb;}
  tr:nth-child(even){background-color:#fcf0f7;}
  #backBtn{margin-bottom: 10px; padding: 10px 20px; background:#d6336c; color:#fff; border:none; border-radius:6px; cursor:pointer;}
</style>
</head>
<body>

<h1>ग्राहक विवरण - एडमिन पैनल</h1>
<button id="backBtn">वापस फॉर्म पर जाएं</button>

<table id="dataTable">
  <thead>
    <tr>
      <th>Section</th><th>Loan Amount</th><th>Interest</th><th>नाम</th><th>जन्म तिथि / परिचय</th>
      <th>आधार कार्ड नंबर</th><th>पैन कार्ड नंबर</th><th>खाता संख्या</th><th>IFSC कोड</th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

<script>
const startLoanAmount=10000;
const increment=5000;
const interestRate=1.2;
const dataTableBody=document.querySelector('#dataTable tbody');
const backBtn=document.getElementById('backBtn');

function loadCustomerData(){
  const data=JSON.parse(localStorage.getItem('loanCustomerData'));
  if(!data) return;
  dataTableBody.innerHTML='';
  data.forEach((item,index)=>{
    const tr=document.createElement('tr');
    tr.innerHTML=`
      <td>${index+1}</td>
      <td>${startLoanAmount+(index*increment)}</td>
      <td>${interestRate}</td>
      <td>${item.name||''}</td>
      <td>${item.dob||''}</td>
      <td>${item.aadhaar||''}</td>
      <td>${item.pan||''}</td>
      <td>${item.account||''}</td>
      <td>${item.ifsc||''}</td>
    `;
    dataTableBody.appendChild(tr);
  });
}
loadCustomerData();

backBtn.onclick=()=>{
  window.location.href='customer_form.html'; // Link to form page
};
</script>

</body>
</html>
