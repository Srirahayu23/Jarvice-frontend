<template>
    <div>
        <table>
        <tr>
            <th rowspan="2">Nama</th>
            <th colspan="3">Nilai</th>
        </tr>
        <tr>
            <th>Kimia</th>
            <th>Fisika</th>
            <th>Biologi</th>
        </tr>
        <tr>
            <td>Robby</td>
            <td>76</td>
            <td>80</td>
            <td>81</td>
        </tr>
        <tr>
            <td>Rendi</td>
            <td>84</td>
            <td>70</td>
            <td>75</td>
        </tr>
        <tr>
            <td>Alfian</td>
            <td>96</td>
            <td>70</td>
            <td>71</td>
        </tr>
    </table>
    </div>
</template>
CSS
<style>
        table {
            border-collapse: collapse;
            width: 100%;
        }
 
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
        }
        th {
            background-color: rgb(19, 110, 170);
            color: white;
        }
        tr:hover {background-color: #f5f5f5;}
</style>