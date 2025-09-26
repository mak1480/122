<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>ตารางเช็คชื่อพนักงาน</title>
  <style>
    body { font-family: "Tahoma", sans-serif; margin: 20px; }
    table { border-collapse: collapse; width: 100%; }
    th, td {
      border: 1px solid #333;
      padding: 6px;
      text-align: center;
    }
    th { background: #f0f0f0; }
    .checked { background: #c8e6c9; }
  </style>
</head>
<body>
  <h2>ตารางเช็คชื่อพนักงาน</h2>
  <table id="checkinTable">
    <thead>
      <tr>
        <th>No</th>
        <th>EMP No</th>
        <th>OS</th>
        <th>NAME</th>
        <th>Location</th>
        <th>Position</th>
        <th>Shift</th>
        <th>เช็คชื่อ</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>1</td><td>660858</td><td>TPT</td><td>นายคณพศ แสนประสิทธิ์</td><td>Packing</td><td>FM</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>2</td><td>920612</td><td>BM</td><td>นายวันชาติ รอดพยุง</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>3</td><td>920640</td><td>BM</td><td>นายทัศนา สุขนัยกิจ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>4</td><td>920745</td><td>BM</td><td>นายธรรมศปณต ปาลกะวงศ์ณอยุธยา</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>5</td><td>123266</td><td>KT</td><td>นายเทิดศักดิ์ พูนเพิ่ม</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>6</td><td>160682</td><td>DSC</td><td>นายอุเทน แจ้งเสน</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>7</td><td>160700</td><td>DSC</td><td>น.ส. พาฝัน ศรีนวล</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>8</td><td>160741</td><td>DSC</td><td>น.ส. ธิติยาทองกล่ำ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>9</td><td>160745</td><td>DSC</td><td>นายธวัช คำใจ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>10</td><td>920839</td><td>BM</td><td>นายธนัญชย์ วีระวิษวัมพร</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>11</td><td>920845</td><td>BM</td><td>นายนัฐพงษ์พงษ์ สร้อยสุวรรณ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>12</td><td>920848</td><td>BM</td><td>นายพีรพงษ์ เปทา</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>13</td><td>920850</td><td>BM</td><td>นายศิริโชค สุครีพ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>14</td><td>950001</td><td>WG</td><td>นายชานน แสนบัวคำ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>15</td><td>950002</td><td>WG</td><td>นายปฐมพงษ์ โพธิ์ขาว</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>16</td><td>950016</td><td>WG</td><td>น.ส.วริศา สัตปานนต์</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>17</td><td>950017</td><td>WG</td><td>น.ส.ณิชารีย์ นิลสินที</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>18</td><td>950021</td><td>WG</td><td>น.ส. กรรณริกา เพียสุริวงษ์</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>19</td><td>035662</td><td>JSR</td><td>น.ส. รัตนาพรต้องติรัมย์</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>20</td><td>950022</td><td>WG</td><td>นายจักรพงศ์ ศรีวิรัตน์</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>21</td><td>920856</td><td>BM</td><td>น.ส. อรอนงศ์ จันทร์กะพ้อ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>22</td><td>920863</td><td>BM</td><td>น.ส.ธัญญา บุญมา</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>23</td><td>920865</td><td>BM</td><td>น.ส. เสาวลักษณ์ กล่ำกลิ่น</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>24</td><td>920847</td><td>BM</td><td>นายเฉลิมพล จิตต์สนธิ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>25</td><td>950015</td><td>WG</td><td>น.ส.รุ่งกาญจน์ ขยันกสิกรณ์</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>26</td><td>950018</td><td>WG</td><td>น.ส.ญาดา สิงห์ทอง</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>27</td><td>950019</td><td>WG</td><td>นายประเสริฐ ของเขตต์</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>28</td><td>160759</td><td>DSC</td><td>นายรามวัฒน์พานิช</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>29</td><td>123329</td><td>KT</td><td>น.ส.กัญญา ศรีมิ่งวงค์</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>30</td><td>035673</td><td>JSR</td><td>น.ส. ฐานิศกันยา จะหวะ</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>31</td><td>035444</td><td>JSR</td><td>นายวรอน เริงรมย์</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
      <tr><td>32</td><td>035689</td><td>JSR</td><td>#N/A</td><td>Packing</td><td>OS</td><td>A</td><td><input type="checkbox"></td></tr>
    </tbody>
  </table>

  <script>
    // บันทึกสถานะ checkbox ไว้ใน LocalStorage
    const checkboxes = document.querySelectorAll("input[type=checkbox]");
    checkboxes.forEach((cb, i) => {
      if(localStorage.getItem("check"+i) === "true") {
        cb.checked = true;
        cb.closest("tr").classList.add("checked");
      }
      cb.addEventListener("change", () => {
        localStorage.setItem("check"+i, cb.checked);
        if(cb.checked){
          cb.closest("tr").classList.add("checked");
        } else {
          cb.closest("tr").classList.remove("checked");
        }
      });
    });
  </script>
</body>
</html>