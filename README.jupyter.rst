
add a jupyter notebook to practice https://ljdursi.github.io/beyond-single-core-R/#/26

Container for R with libraries for LBNL Energy Technology Area project
Now with Jupyter Notebook server

Start jupyter notebook web server (on specific port, eg 6997):

docker run -p 6997:6997 -v "$PWD":/mnt -it --entrypoint=/opt/conda/bin/jupyter  tin6150/beyond-single-core-r  lab --allow-root  --no-browser --port=6997 --ip=0.0.0.0

Point web browser to something like
  http://127.0.0.1:6997/ 
  http://hima.lbl.gov:6997/ 
and paste the token URL link shown on the terminal console


~~~~


in branch jupyter

adding a docker container with jupyter lab
to run notebook
to try out the examples.

# adopted from r4envids

tin
2020.0926


original author Jonathan Dursi
web page: 
https://ljdursi.github.io/beyond-single-core-R/#/1
