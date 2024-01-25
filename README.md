# warehouse_mansh1
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
      }

      .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 20px;
        background-color: #f2f2f2;
      }

      .header {
        display: flex;
        justify-content: space-between;
        width: 100%;
        margin-bottom: 20px;
      }

      .logo {
        font-size: 24px;
        font-weight: bold;
      }

      .nav {
        display: flex;
      }

      .nav a {
        margin: 0 10px;
        font-size: 18px;
        text-decoration: none;
        color: #333;
      }

      .card {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 300px;
        padding: 20px;
        background-color: #fff;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        margin: 10px;
      }

      .card h2 {
        font-size: 24px;
        margin-bottom: 10px;
      }

      .card p {
        font-size: 16px;
        margin-bottom: 10px;
      }

      .card span {
        font-size: 14px;
        color: #666;
      }

      .table {
        display: flex;
        width: 100%;
        margin-top: 20px;
      }

      .table th {
        font-size: 16px;
        font-weight: bold;
        padding: 10px;
        background-color: #f2f2f2;
        border: 1px solid #ddd;
      }

      .table td {
        font-size: 16px;
        padding: 10px;
        border: 1px solid #ddd;
      }

      .total {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        margin-top: 20px;
        font-size: 18px;
        font-weight: bold;
      }

      .total span {
        font-size: 16px;
        color: #666;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="header">
        <div class="logo">Warehouse 100 in 1</div>
        <div class="nav">
          <a href="#">Dashboard</a>
          <a href="#">Product</a>
          <a href="#">Customers</a>
          <a href="#">Income</a>
          <a href="#">Help</a>
          <a href="#">Upgrade to PRO</a>
        </div>
      </div>
      <div class="card">
        <h2>Project Managers</h2>
        <p>Abubakirova Manshuk V</p>
        <p>Aliyeva Aigerim</p>
        <p>Abdulaev Ruslan</p>
      </div>
      <div class="card">
        <h2>Overview</h2>
        <p>Monthly Earning</p>
        <p>Jan - $150k</p>
        <p>Feb - $198k ↑ 37.8% this month</p>
      </div>
      <table class="table">
        <tr>
          <th>Product Name</th>
          <th>Product Sell</th>
          <th>Earning</th>
          <th>Stock</th>
          <th>Price</th>
          <th>Customers</th>
          <th>Total Sales</th>
        </tr>
        <tr>
          <td>Soya Milk "Alpro"</td>
          <td>101</td>
          <td>$198k</td>
          <td>60 in stock</td>
          <td>$83.56</td>
          <td>$45.30</td>
          <td>$89k 11% this week</td>
        </tr>
        <tr>
          <td>Chocolate muffins</td>
          <td>99</td>
          <td>$120k</td>
          <td>40 in stock</td>
          <td>$59.00</td>
          <td>$65.00</td>
          <td>$45k 34% this week</td>
        </tr>
        <tr>
          <td>Paper cups</td>
          <td>256</td>
          <td>$150k</td>
          <td>300 in stock</td>
          <td>not for sale</td>
          <td>$35.00</td>
          <td>$120k 65% this week</td>
        </tr>
        <tr>
          <td>Cleansing chemicals</td>
          <td>45</td>
          <td>$45k</td>
          <td>15 in stock</td>
          <td>not for sale</td>
          <td>$25.00</td>
          <td>$30k 25% this week</td>
        </tr>
      </table>
      <div class="total">
        <span>Balance: $2.4k ✓
