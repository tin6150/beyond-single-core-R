
Container for R with libraries and data from Jonathan Dursi "Beyond Single-Core R" tutorial
This version add a jupyter notebook to practice 
Original slides at https://ljdursi.github.io/beyond-single-core-R/#/1

Usage

Start jupyter notebook web server (on specific port, eg 6997):

docker run -p 6997:6997 -v "$PWD":/mnt -it --entrypoint=/opt/conda/bin/jupyter  tin6150/beyond-single-core-r  lab --allow-root  --no-browser --port=6997 --ip=0.0.0.0

Point web browser to something like
  http://127.0.0.1:6997/ 
and paste the token URL link shown on the terminal console


 /mnt is a mount of the current dir (PWD) where you started the docker process, and files written there will persist after the container is terminated.  (Other files inside the container are ephemeral!)

~~~~


in branch jupyter

adding a docker container with jupyter lab
to run notebook
to try out the examples.

# adopted from r4envids

tin
2020.0926

