# leetcode---1527
patients with a condition
// code in mysql
SELECT *
FROM Patients
WHERE
  conditions LIKE 'DIAB1%'
  OR conditions LIKE '% DIAB1%'
