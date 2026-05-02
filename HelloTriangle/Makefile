CFLAGS = -std=c++17 -g -O0
LDFLAGS = -lglfw -lvulkan -ldl -lpthread -lwayland-client

.PHONY: test clean

test: HelloTriangle
	./HelloTriangle

clean:
	rm -f HelloTriangle

HelloTriangle: main.cpp
	g++ $(CFLAGS) -o HelloTriangle main.cpp $(LDFLAGS)
