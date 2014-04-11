CXX = g++
INCLUDES= -I./
CXXFLAGS = -g $(INCLUDES)
SRCM= ../CBasicMath.cpp
OBJM = $(SRCM:.cpp)
LINKFLAGS= -lcppunit

testbasicmath: TestBasicMath.cpp $(OBJM)
	$(CXX) -o $@ CBasicMath.cpp TestBasicMath.cpp $(OBJM) $(LINKFLAGS) $(LINKFLAGSLOG4) $(LIBLOG)

# Default compile

.cpp.o:
	$(CXX) $(CXXFLAGS) -c $< -o $@
          