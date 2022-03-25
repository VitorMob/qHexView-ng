QHexView-ng
==========

This is Qt widget for display binary data in traditional hex-editor style. This widget doesn`t have any editing capabilities. Only viewing and copying.


GUI
-----

![image](assets/qhexview-ng.png)


Building the example
-----

* cd  QHexView-ng
* mkdir build
* cd build
* cmake ..
* make


Usage
-----
	...
	QByteArray data;
	...
	QHexView *phexView = new QHexView;
	...
	phexView -> setData(data);
	...
