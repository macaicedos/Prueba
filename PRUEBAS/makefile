matlab= matlab -nodisplay
#matlab = /usr/local/MATLAB-R2012b/bin/matlab -nodisplay
#matlab = /Applications/MATLAB_R2010b.app/bin/matlab -nodisplay

runfile=run

all:
	echo 'make what bitch !?!'

clean:
	@rm -fv *.msh
	@rm -fv *.pasNoConv
	@rm -fv *.res
	@rm -fv *.cur*
	@rm -fv *.vv
	@rm -fv *.mat
	@rm -fv *.eps
	@rm -fv out

run:
	@${matlab} -nodisplay -r ${runfile}

nhrun:
	@nohup make run > out &

eps:
	@gnuplot plot.gp