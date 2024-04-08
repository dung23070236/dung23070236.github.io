<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewpor" content="width=device-width,initial-scale=1.0">
        <title>Báo cáo tài chính</title>
    </head>
    <body>
        <h1 class="heading-primary">           
            Báo cáo tài chính  
        </h1>
        <table width="400" boder="2" cellpadding="5" align="center">
            <tr>
                    <td>Danh mục</td>
                    <td>Số tiền</td>
            </tr>
            <tr>
                <td>Danh mục A</td>
                <td>
                    <input type="number" id="num1" >
                </td>
            </tr>
            <tr>
                <td>Danh mục B</td>
                <td>
                    <input type="number" id="num2">
                </td>
            </tr>
            <tr>
                <td>Danh mục C</td>
                <td>
                    <input type="number" id="num3">
                </td>
            </tr>
            <tr>
                <td>Tổng</td>
                <td>
                    <button onclick="tinhTong()">Tổng</button>
                    <p id="ketqua"></p>
                </td>
                <script>
                    function tinhTong() {
                        var num1 = document.getElementById("num1").value;
                        var num2 = document.getElementById("num2").value;
                        var num3 = document.getElementById("num3").value;
                        var tong = parseInt(num1) + parseInt(num2) + parseInt(num2)
                        document.getElementById("ketqua").innerHTML = tong;
                    }
                </script>
            </tr>
        </table>
    </body>
</html>
