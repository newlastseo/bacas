<template>
  <div>
    <img alt="bacas logo" src="./assets/BacasLogo.jpg" style="float: left" />
    <p style="display: inline-block">
      1006 Windsor Lakes Blvd, Suite 150, Conroe, TX 77384
    </p>
    <p style="display: inline-block">Tel: 713-266-0808 Fax: 713-266-0809</p>
    <p style="display: inline-block">CLIA#: 45D2057171 Tax ID:xx-xxx-xxxx</p>
  </div>
  <hr />
  <table>
    <tr>
      <th>Patient Information</th>
      <th>Account Information</th>
      <th>Sample Information</th>
    </tr>
    <tr style="text-align: left">
      <td style="font-size: 12px">
        Patient: {{ name[0] }} <br />
        DOB: {{ DOB[0] }} <br />
        Age:{{ age[0] }}<br />
        Gender:({{ Sex[0] }})<br />
        MRN: BS42400<br />
        Address: {{ address[0] }}<br />
        Temp: Unknown
      </td>
      <td style="font-size: 12px">
        Order by: Dr.Bond <br />
        PON: 243-2-137400<br />
        Account number: 0243<br />
        Agency: Dr. Nelson Bond<br />
        1917 Ashland Street #160 <br />
        Houston TX 77008 <br />
        844-342-2227
      </td>
      <td style="font-size: 12px">
        Accession: 210624011 <br />
        Collected: 06/22/2021 08:00 AM<br />
        Received: 06/24/2021 09:52 AM<br />
        Reported: 06/24/2021 04:44 PM<br />
        Status: Final <br />
        Other ID: N/A
      </td>
    </tr>
  </table>
  <h4>Medication Prescribed: Suboxone</h4>
  <table>
    <thead style="text-align: center">CONFIRMATION RESULTS SUMMARY</thead>
    <tbody>
      <tr>
        <th>1</th>
        <th>2</th>
      </tr>
      <tr>2</tr>
    </tbody>
    

  </table>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      name: ["Ben Seo", "Shawn Liang"],
      DOB: ["03 / 09 / 1984"],
      age: [37],
      Sex: ["M"],
      address: ["9339 Cantata t, Jersey Village TX 77040"],
    };
  },
  components: {},
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
img {
  height: 120px;
}
table,
th {
  border: 1px solid black;
}
table {
  width: 100%;
}
td {
  width: 33.33%;
}
</style>
