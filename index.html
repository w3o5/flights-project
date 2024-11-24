<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نظام توزيع الرحلات</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f5f5f5;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #333;
        }
        label {
            font-size: 18px;
            margin: 10px;
        }
        select, button {
            font-size: 16px;
            padding: 5px 10px;
            margin: 10px;
        }
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <h1>نظام توزيع الرحلات</h1>
    <label for="departure">مدينة المغادرة:</label>
    <select id="departure">
        <option value="Riyadh">الرياض</option>
        <option value="Jeddah">جدة</option>
    </select>

    <label for="arrival">مدينة الوصول:</label>
    <select id="arrival">
        <option value="Dubai">دبي</option>
        <option value="Cairo">القاهرة</option>
    </select>

    <button onclick="searchFlights()">بحث</button>

    <table id="results">
        <thead>
            <tr>
                <th>مدينة المغادرة</th>
                <th>مدينة الوصول</th>
                <th>وقت المغادرة</th>
                <th>مدة الرحلة</th>
            </tr>
        </thead>
        <tbody>
            <!-- النتائج ستظهر هنا -->
        </tbody>
    </table>

    <script>
        // بيانات الرحلات
        const flights = [
            { departure: "Riyadh", arrival: "Dubai", time: "10:00 AM", duration: "2 hours" },
            { departure: "Riyadh", arrival: "Cairo", time: "12:00 PM", duration: "3 hours" },
            { departure: "Jeddah", arrival: "Dubai", time: "2:00 PM", duration: "2.5 hours" },
            { departure: "Jeddah", arrival: "Cairo", time: "4:00 PM", duration: "3.5 hours" }
        ];

        // دالة البحث عن الرحلات
        function searchFlights() {
            const departureCity = document.getElementById("departure").value;
            const arrivalCity = document.getElementById("arrival").value;

            const resultsTable = document.getElementById("results").getElementsByTagName("tbody")[0];
            resultsTable.innerHTML = ""; // مسح النتائج السابقة

            // تصفية الرحلات بناءً على اختيار المستخدم
            const filteredFlights = flights.filter(flight =>
                flight.departure === departureCity && flight.arrival === arrivalCity
            );

            // عرض النتائج
            if (filteredFlights.length > 0) {
                filteredFlights.forEach(flight => {
                    const row = resultsTable.insertRow();
                    row.innerHTML = `
                        <td>${flight.departure}</td>
                        <td>${flight.arrival}</td>
                        <td>${flight.time}</td>
                        <td>${flight.duration}</td>
                    `;
                });
            } else {
                const row = resultsTable.insertRow();
                row.innerHTML = ⁠ <td colspan="4">لا توجد رحلات متاحة</td> ⁠;
            }
        }
    </script>
</body>
</html>
