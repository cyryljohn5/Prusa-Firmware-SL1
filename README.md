How to build image
==================

git clone ssh://git@gitlab.webdev.prusa3d.com:22443/hw/a64/oe.git

cd oe

./oe-layertool-setup.sh

cd build

source conf/setenv

bitbake sla-image