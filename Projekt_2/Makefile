NAME = proj2
LOGIN = xspirk01

all:
	latex $(NAME).tex
	latex $(NAME).tex
	dvips -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps

clean:
	rm -f $(NAME).{aux,dvi,log,pdf,ps}