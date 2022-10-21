docker-compose-script:
	cd /app/report

	latexmk -pdf -output-directory=/temp/ -jobname=MOD.PO4.190333-01_81_00 main.tex
	
	cp /temp/*.pdf /build/
