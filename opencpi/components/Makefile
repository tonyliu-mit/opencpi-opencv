
# #####
#
#  Copyright (c) Mercury Federal Systems, Inc., Arlington VA., 2009-2010
#
#    Mercury Federal Systems, Incorporated
#    1901 South Bell Street
#    Suite 402
#    Arlington, Virginia 22202
#    United States of America
#    Telephone 703-413-0781
#    FAX 703-413-0784
#
#  This file is part of OpenCPI (www.opencpi.org).
#     ____                   __________   ____
#    / __ \____  ___  ____  / ____/ __ \ /  _/ ____  _________ _
#   / / / / __ \/ _ \/ __ \/ /   / /_/ / / /  / __ \/ ___/ __ `/
#  / /_/ / /_/ /  __/ / / / /___/ ____/_/ / _/ /_/ / /  / /_/ /
#  \____/ .___/\___/_/ /_/\____/_/    /___/(_)____/_/   \__, /
#      /_/                                             /____/
#
#  OpenCPI is free software: you can redistribute it and/or modify
#  it under the terms of the GNU Lesser General Public License as published
#  by the Free Software Foundation, either version 3 of the License, or
#  (at your option) any later version.
#
#  OpenCPI is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#  GNU Lesser General Public License for more details.
#
#  You should have received a copy of the GNU Lesser General Public License
#  along with OpenCPI.  If not, see <http://www.gnu.org/licenses/>.
#
########################################################################### #

OCPI_CDK_DIR=../ocpi

Implementations = \
	adc.rcc \
	adc_unpack.rcc \
	bias.hdl \
	convert_s16_f32.rcc \
	copy.rcc \
	dac.rcc \
	ddc.hdl \
	delay.hdl \
	delay.rcc \
	framegate.hdl \
	framegate.rcc \
	morph_mean.rcc \
	psd.hdl \
	sma.hdl \
	split1x2.rcc \
	splitter2x2.hdl \
	splitter2x2.rcc \
	testmulti.rcc \
	testzc.rcc \
	sobel.rcc \
	scharr.rcc \
	laplace.rcc \
	dilate.rcc \
	erode.rcc \
	blur.rcc \
	median.rcc \
	gaussian_blur.rcc \
	canny.rcc \
	canny_partial.rcc \
	corner_eigen_vals_vecs.rcc \
	min_eigen_val.rcc \
	good_features_to_track.rcc \
	optical_flow_pyr_lk.rcc \
	sobel_32f.rcc \
#	bilateral.rcc \
#	pyr_up.rcc \
#	pyr_down.rcc

#	wbr.hdl 

HdlTargets=xc5vsx95t-2-ff1136 xc5vlx50t-1-ff1136 xc6vlx240t-1-ff1156 
#  xc5vlx330t-2-ff1738

ifndef OCPI_RUNTIME_HOST
RccTargets=$(HostTarget)
else
RccTargets=$(OCPI_RUNTIME_HOST)
endif

include $(OCPI_CDK_DIR)/include/lib.mk
