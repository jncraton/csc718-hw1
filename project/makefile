all: myhttpd1 myhttpd2 myhttpd3

%: %.cpp
	gcc -pthread -o $@ $<

clean:
	rm -f myhttpd1 myhttpd2 myhttpd3