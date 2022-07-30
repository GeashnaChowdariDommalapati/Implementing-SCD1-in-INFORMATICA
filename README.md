<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Hey Everyone!🕹️&animation=fadeIn&type=waving&color=gradient&height=100"/>
</p>

<h1 align = center>Implementing-SCD1-in-INFORMATICA</h1>
The SCD Type 1 method is used when there is no need to store historical data in the Dimension table. The SCD type 1 method overwrites the old data with the new data in the dimension table. Identifying the new record and inserting it in to the dimension table.
<hr>
<br>
<h3>Source Table Schema</h3>

![scd1_src_tbl](https://user-images.githubusercontent.com/107995861/177060576-67e82bbe-3cf8-4f95-9dee-5aca2ed3a70d.jpeg)

<br>
<h3>Target Table Schema</h3>

![scd1_tgt_tbl](https://user-images.githubusercontent.com/107995861/177060596-1b7ba6f4-16c6-47ab-bf20-f54e9978f9f9.jpeg)

<br>
<h3>Data in the Source table Employee</h3>

![scd1_src_emp](https://user-images.githubusercontent.com/107995861/177060503-c89bb5c9-8bb9-4f98-a883-747452f02845.jpeg)

<br>
<h3>Mapping of SCD1 (Full view)</h3>

![scd1_mapping](https://user-images.githubusercontent.com/107995861/177060424-c799f06d-6ea7-4010-b757-cb0cf10fd0c3.jpeg)

<br>
<h3>Mapping of SCD1 (Iconic view)</h3>

![scd1_mapping_iconic](https://user-images.githubusercontent.com/107995861/177060651-e91c67a0-268c-4a49-a3b0-a438ff10f076.jpeg)

<br>
<h3>After first workflow target table data</h3>

![scd1_tgt_initial](https://user-images.githubusercontent.com/107995861/177060690-dcd3e651-dcc4-4107-bd30-ab91890f8d78.jpeg)

<br>
<h3>Inserting and Updating the Data in Source Table</h3>

![scd1_src_emp_modified](https://user-images.githubusercontent.com/107995861/177060720-59a457d8-6bcd-4433-938f-c8d68ce1bb3d.jpeg)

<br>
<h3>After data modified in source table and implementing scd1 the output of target table is</h3>

![scd1_tgt_output](https://user-images.githubusercontent.com/107995861/177060754-69dd5b85-f588-4519-91e3-f15b2ef70d18.jpeg)
