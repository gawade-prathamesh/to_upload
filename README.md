select to_date(LCHG_TIME,'YYYY-MM-DD"T"HH24:MI:SS') from tbaadm.daily_tran_header_table where rownum < 5


2023-09-12T05:14:26


SELECT TO_DATE(LCHG_TIME, 'YYYY-MM-DD"T"HH24:MI:SS') AS CONVERTED_TIME
FROM tbaadm.daily_tran_header_table
WHERE ROWNUM < 5;
