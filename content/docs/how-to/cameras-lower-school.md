

## Hardware
`MCAIPCAM1` or `10.10.10.9`

## Viewing
To view cameras:
Find the login information in our [IT Manual](https://docs.google.com/document/d/1FTnrAtKRgohreLQcMQWQcB9kovXHajtX/edit#heading=h.5nez4csxsxs2).


## Configuring cameras
To configure each camera using `MCAIPCAM1`, run Axis IP Utility, then select the  camera to configure and login using information from [IT Manual](https://docs.google.com/document/d/1FTnrAtKRgohreLQcMQWQcB9kovXHajtX/edit#heading=h.5nez4csxsxs2).

# Setup
the default Axis camera IP is `192.168.0.90`.  Put a laptop on the `192.168.0.x` LAN to access camera and configure.

	Subnet Mask:`255.255.255.0`
	Default Router:`192.168.1.254`


## Resetting
To reset camera, press and hold control button for 15 seconds while powering on until amber light stops flashing.


## Orchid

 Servers: 
 * MCACAM1   `10.10.10.19`	`192.168.1.254`
* MCACAM2 `10.10.10.9`		`192.168.1.253`
* MCACAM3 `10.10.10.18`		`192.168.1.252`


Once there, open a browser and to view, type in `10.10.10.9` in address bar.  Externally, `198.74.252.150`, login using creds from our [IT Manual](https://docs.google.com/document/d/1FTnrAtKRgohreLQcMQWQcB9kovXHajtX/edit#heading=h.5nez4csxsxs2).

## Adding older cameras
To add older Axis cameras, select Driver Generic RTSP and use this URL: 
* `rtsp://ip_address/mpeg4/media.amp` 		(substituting in the camera’s IP address)


## Camera IP Ranges

* Exterior N		`192.168.1.2 – 1.09`
* Exterior E		`1.10 – 1.19`
* Exterior S		`1.20 – 1.29`
* Exterior W		`1.30 – 1.39`


* NC Hallways 	`1.40 – 1.59`
* SC Hallways	`1.60 – 1.79`
* UC Hallways	`1.80 – 1.99`
* NC Rooms		`1.100 – 1.154`
* Cafeteria		`1.155 – 1.158`
* SC Rooms		`1.159 – 1.199`
* UC Rooms		`1.200 – 1.240`
	
