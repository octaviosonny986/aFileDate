# aFileDate
;~ Get Created Timestamp Local $aFileDate = FileGetTime(@ScriptFullPath, 1, 0) MsgBox(4096, "FileDate", "Year : " &amp; $aFileDate[0] &amp; @CRLF &amp; "Month : " &amp; $aFileDate[1] &amp; @CRLF &amp; "Day : "  &amp; $aFileDate[2] &amp; @CRLF &amp; "Hour : " &amp; $aFileDate[3] &amp; @CRLF &amp; "Minutes : " &amp; $aFileDate[4] &amp; @CRLF &amp; "Seconds : " &amp; $aFileDate[5])
