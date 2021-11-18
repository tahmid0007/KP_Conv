# KP_Conv
From V3 to V4, the main difference is in the number of threads or workder = 10 or 0, carefully handle the synchronization() in trainer script. Also V4 had a os.kill process command in the very last line of the train_s3dis file which resulted in spyder showing weird error window.
Also note that V4 has a visualize_kp_conv script. This needs some sort of downsampling otherwise plot shows empy grid on browser.
