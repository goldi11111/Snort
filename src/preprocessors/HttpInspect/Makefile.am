## $Id
AUTOMAKE_OPTIONS=foreign no-dependencies

noinst_LIBRARIES = libhttp_inspect.a

libhttp_inspect_a_SOURCES = 

SUBDIRS = include utils user_interface session_inspection mode_inspection  \
          anomaly_detection event_output server client normalization 

libhttp_inspect_a_LIBADD = \
user_interface/hi_ui_config.o \
user_interface/hi_ui_server_lookup.o \
user_interface/hi_ui_iis_unicode_map.o \
session_inspection/hi_si.o \
mode_inspection/hi_mi.o \
anomaly_detection/hi_ad.o \
utils/hi_util_kmap.o \
utils/hi_util_xmalloc.o \
utils/hi_util_hbm.o \
utils/hi_cmd_lookup.o \
utils/hi_paf.o \
event_output/hi_eo_log.o \
client/hi_client.o \
client/hi_client_norm.o  \
server/hi_server.o \
server/hi_server_norm.o \
normalization/hi_norm.o 

INCLUDES = @INCLUDES@
