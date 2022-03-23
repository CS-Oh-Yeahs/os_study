# 운영체제 스터디 OS오예스 문제모음 
> 멤버별로 작성한 답변은 해당하는 멤버의 토글 버튼을 누르면 확인하실 수 있습니다!  
> 답변 정렬 기준은 이름 가나다 순 입니다 🤗
> 
## Introduction to Operating Systems
#### 운영체제의 정의를 설명하고 그 기능에 대해 아는대로 말해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    운영체제는 컴퓨터 하드웨어 바로 위에 설치되어 사용자 및 다른 소프트웨어와 하드웨어를 연결하는 소프트웨어 계층이다. 운영체제는 사용자가 컴퓨터를 쉽게 다룰 수 있게 GUI 인터페이스 제공하고, 하드웨어 자원을 효율적으로 사용할 수 있게 도와준다.
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    운영체제란 하드웨어 바로 윗단에 위치한 소프트웨어로 하드웨어를 사용자 및 다른 소프트웨어들과 연결해주는 역할을 수행합니다. 하드웨어 쪽 인터페이스로서는 한정된 컴퓨터의 자원을 효율적이고 형평적으로 관리하기 위한 자원 관리자 역할을 하며, 사용자 쪽 인터페이스로서는 사용자로 하여금 하드웨어의 복잡성을 전부 알고 있지 않아도 컴퓨터를 편리하게 사용할 수 있도록 환경을 제공하는 역할을 합니다. 더불어, 운영체제 자신 및 컴퓨터 시스템을 보호하는 기능 또한 담당합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    운영체제는 컴퓨터 하드웨어 바로 위에 설치되어 사용자 및 다른 소프트웨어와 하드웨어를 연결하는 소프트웨어 계층입니다. 운영체제는 사용자가 컴퓨터 시스템을 편리하게 사용할 수 있는 환경을 제공하고, 컴퓨터 시스템 자원을 효율적으로 사용할 수 있도록 관리합니다.
  </div>
</details>

#### 운영체제 운용 기법 중 시분할 시스템에 대하여 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    시분할 시스템은 여러 작업을 수행할 때 CPU를 일정한 시간 단위로 프로그램에게 할당하여 처리해줌으로써 각 사용자에게 독립된 컴퓨터를 사용하는 느낌을 준다. 라운드 로빈(Round Robin)방식이라고도 한다.
    하나의 CPU는 같은 시점에서 여러 개의 작업을 동시에 수행할 수 없기 때문에, CPU의 전체 사용시간을 작은 작업 시간량으로 쪼개어 그 시간량 동안만 번갈아가면서 CPU를 할당하여 각 작업을 처리하는 방법이다. 모든 작업이 동시에 진행되는 것처럼 대화식 처리가 가능하다. 각 작업에 대한 응답시간을 최소화 하는 것이 목적이다.
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    시분할 시스템이란 오늘날 범용적인 컴퓨터에 가장 많이 활용되는 운용 기법으로, 여러 작업이 사용하고자 할 때에 아주 작은 시간 단위로 나누어 한정된 자원을 나눠쓸 수 있도록 하는 방식으로, 고전적 운용 기법인 일괄처리방식에 비해 짧은 응답 시간을 갖기에 사용자와의 상호작용성이 높아진다는 장점이 있습니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    현대의 운영체제 처리 방식으로, 여러 작업을 수행할 때 컴퓨터의 처리 능력을 일정한 시간 단위로 분할하여 사용하는 것입니다. 컴퓨터가 사용자들의 프로그램을 번갈아가며 처리해줌으로써 각 사용자에게 독립된 컴퓨터를 사용하는 느낌을 주게 됩니다.
  </div>
</details>

#### 운영체제의 개념을 좁은 의미와 넓은 의미로 나누어 간략하게 설명하시오.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    운영체제의 좁은 의미는 운영체제 커널을 의미하고 커널은 운영체제의 핵심 부분임으로 전원이 켜짐과 동시에 메모리에 상주합니다. 운영체제의 넓은 의미는 운영체제의 커널과 각종 주변 유틸리티 시스템을 포함한 개념입니다.
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    좁은 의미의 운영체제는 항상 메모리에 상주하는 '커널'을 의미하며, 넓은 의미의 운영체제는 커널 이외에도 각종 주변 시스템 유틸리티까지 포함합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    좁은 의미의 운영체제는 커널을 의미합니다. 커널은 운영 체제의 핵심 부분으로 메모리에 상주하는 일부분을 이야기합니다. 반면 넓은 의미의 운영체제는 커널과 각종 주변 시스템 유틸리티를 포함한 개념입니다.
  </div>
</details>

***

## System Structure & Program Execution
#### 사용자 프로그램이 I/O를 요청했을 때 일어나는 일을 설명해보시오.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    사용자는 직접 입출력 장치에 접근할 수 없기 때문에 시스템 콜을 하여 운영체제에게 I/O 작업을 요청한다. 운영체제는 요청받은 I/O 명령을 사용자 프로그램 모드가 아닌 커널 모드에서 해당 요청에 맞는 처리코드를 수행하게 된다. 예를 들어 디스크에서 자료를 읽어오는 시스템 콜이라면, CPU가 디스크 컨트롤러에게 데이터를 읽어오라는 명령을 내린다.
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    I/O 작업은 보안 상 문제가 될 수 있는 작업이므로 운영체제만 수행 가능합니다. 따라서, 사용자 프로그램이 I/O 작업을 하고자 할 때에는 시스템콜을 통해 CPU에게 소프트웨어 인터럽트를 발생시키게 됩니다. 인터럽트를 발견한 CPU는 제어권을 운영체제에게 넘겨주며, 운영체제는 디바이스 컨트롤러에게 I/O 작업을 수행할 것을 명령합니다. I/O 작업이 끝나면 이번에는 디바이스 컨트롤러가 CPU에게 I/O 작업이 완료되었음을 알리기 위해 하드웨어 인터럽트를 발생시키며, 인터럽트를 발견한 CPU는 해당 디바이스의 로컬 버퍼에 저장된 데이터를 메인 메모리로 전달해오고 운영체제는 이전에 I/O 작업을 요청한 프로그램을 다시 CPU를 할당받을 수 있는 상태로 전환시킵니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    먼저, CPU가 운영체제에게 I/O 요청 보낸다. 그 즉시 CPU의 제어권이 운영체제로 넘어가게 되고 CPU는 지금까지 하던 일을 멈추고 프로그램의 현재 상태를 저장한 후, 인터럽트에 의해 처리해야 할 커널의 루틴으로 이동한다. 루틴에 따라 입출력 장치의 컨트롤러에게 연산을 요청하고, 컨트롤러는 로컬버퍼로 해당 데이터를 읽어온다. 컨트롤러가 데이터를 읽어오는 동안 운영체제는 CPU를 프로그램 B에 할당하여 CPU가 프로그램 B의 작업을 처리하도록 한다. 이후 입출력 컨트롤러부터 CPU로 데이터 입출력 작업이 완료되었다는 인터럽트가 전달되면 CPU는 B에 대한 수행 정보를 저장하고 인터럽트를 처리하게 된다.
  </div>
</details>

#### DMA 컨트롤러의 기능을 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    CPU가 입출력 장치들의 메모리 접근 요청에 의해 자주 인터럽트 당하는 것을 막아주어서 CPU에 발생하는 인터럽트의 빈도를 줄여 CPU를 효율적으로 관리할 수 있게 도와주는 역할을 한다.
DMA를 사용하면 CPU가 로컬버퍼에서 메모리로 읽어오는 작업을 DMA가 대행한다. DMA는 바이트 단위가 아니라 블록이라는 큰 단위로 정보를 메모리로 읽어온 후에 CPU에게 인터럽트를 발생시켜 작업이 끝난 것을 알린다.
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    DMA 컨트롤러는 CPU 외에 직접 메모리에 접근할 수 있는 컨트롤러입니다. 원칙적으로 메인 메모리에는 CPU만 접근이 가능하지만, 빈번한 I/O 작업이 인터럽트를 걸 경우 CPU의 작업이 방해받는 문제가 발생합니다. 따라서, 해당 문제를 해결하고 CPU의 효율성을 높이기 위해 DMA 컨트롤러는 I/O 작업이 완료되면 해당 I/O 디바이스의 로컬 버퍼에 저장된 값을 메인 메모리로 옮겨와 주는 역할을 대행하고 여러 I/O 작업 완료 인터럽트를 모아 CPU에게 한 번만 인터럽트를 발생시킵니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    일종의 컨트롤러로서, CPU가 입출력 장치들이 수시로 발생시키는 인터럽트로 인해 사용상의 효율이 떨어지는 것을 막아주고자 CPU대신 로컬버퍼에서 메모리로 입출력 관련 데이터를 읽어오는 작업을 대신 처리한다.
  </div>
</details>

#### 시스템콜에 대해 설명해보세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    시스템 콜이란 사용자 프로그램이 특권명령을 수행하기 위해 운영체제에게 해당 작업을 요청하는 행위이다. 시스템 콜은 일종의 소프트웨어적인 인터럽스로서 사용자 프로그램이 시스템 콜을 할 경우 트랩이 발생해 CPU의 제어권이 운영체제로 넘어가게 된다. 그러면 운영체제는 해당 시스템 콜을 처리하기 위한 루틴으로 가서 정의된 명령을 수행한다.
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    시스템콜이란 입출력, 메모리 접근과 같이 보안 상의 문제로 인해 운영체제만 수행할 수 있는 서비스를 이용하기 위해 사용자 프로그램이 커널 공간에 있는 함수를 호출하는 인터페이스를 말합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    시스템콜이란 프로그램이 입출력 작업을 수행하기 위해 운영체제의 함수를 호출하는 것이다.
  </div>
</details>

***

## Process
#### 프로세스 문맥교환이 어떠한 상황에서 발생하는지 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    문맥교환이란 타이머 인터럽트가 발생한 경우 또는 I/O 작업 요청 등이 발생한 경우 CPU의 제어권이 실행 중이던 프로세스에서 다른 프로세스로 이양되는 과정으로, 현재 수행 중이던 프로세스의 문맥을 PCB에 저장하고 다음 실행할 프로세스의 문맥을 PCB에서 가져오는 것입니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### 적은 양의 메모리를 많은 프로세스에게 할당할 때 발생하는 문제점과 이를 해결하기 위해 개발된 스케줄러를 하나만 선택하여 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    프로세스 당 보유하고 있는 메모리의 양이적어지게 되면, 당장 실행해야하는 프로세스의 주소 공간을 메모리에 올려둘 수 없을 정도로 메모리가 부족해질 수 있으며, 해당 경우에는 디스크 입출력이 빈번해지며 성능이 저하되는 문제가 발생합니다. 이와 같은 문제를 해결하기 위해 swapper라고도 불리는 중기 스케줄러는 봉쇄 상태 등 CPU를 할당받을 수 없는 프로세스로부터 메모리를 빼앗아 그 내용을 디스크로 swap-out 하며 메모리에 적재된 프로세스의 수를 동적으로 조절하고 여유 공간을 확보합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### 프로세스 제어블록이란 무엇인지 설명하고 프로세스 제어블록의 요소들에 대해 아는대로 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    Process Control Block 이란 커널에서 각 프로세스를 관리하기 위해 필요한 정보를 갖고 있는 자료구조로, 운영체제의 프로세스 관리 상 필요한 정보인 PID, 프로세스 상태, 스케줄링 우선순위 등, CPU 운영 상 필요한 정보인 Program Counter, Registers 등, 그리고 메모리 및 파일과 같은 자원 관련 stack/data/code의 위치 정보, open file descriptors 등을 포함합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### 4가지의 프로세스 상태에 대해 각각 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    Ready는 실행을 위한 다른 모든 준비가 완료되고 CPU 할당만을 기다리는 상태이며, Running은 CPU가 할당되어 instructions가 수행 중인 상태, Blocked는 입출력 작업 등과 같이 많은 시간을 필요로 하는 이벤트 발생으로 인해 CPU를 할당 받더라도 당장 insturctions 수행이 불가능한 상태, Suspended는 사용자의 일시중지 또는 중기 스케줄러의 swap-out 등 사유로 인해 외부적인 사유로 인해 프로세스의 수행이 중지된 상태 입니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### 프로세스와 스레드 각각의 개념을 설명하고, 멀티프로세스보다 멀티스레드가 효율적인 이유를 말씀해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    프로세스는 실행 중인 프로그램, 즉 운영체제로부터 시스템 자원을 할당받는 단위이며, 스레드는 한 프로세스의 할당 받은 자원 내에서 CPU 수행이 실행되는 흐름의 단위 입니다. 프로세스는 만들 때마다 자료구조를 별도로 생성해야 하므로 메모리가 낭비되고, 프로세스를 생성하거나 프로세스 문맥교환을 수행할 때마다 오버헤드가 큰 반면, 스레드는 code/data 영역 및 운영체제의 자원과 같이 공유할 수 있는 자원들을 최대한 공유하기 때문에 보다 효율적이고 경제적입니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### 스레드의 장점을 아는 대로 전부 말씀해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    스레드는 첫째, 빠른 응답성을 가집니다. 한 프로세스 내에서 특정 스레드가 blocked 상태여도 다른 스레드는 CPU를 할당받아 수행할 수 있습니다. 둘째, 자원을 공유합니다. PC, registers, stack 이외의 공유 가능한 자원들을 공유하여 자원을 절약합니다. 셋째, 프로세스를 여러 개 만드는 것에 비해 경제적입니다. 멀티프로세스는 생성 및 문맥교환 과정에서 많은 오버헤드를 동반하지만, 스레드는 최대한 많은 자원과 문맥을 공유하여 보다 낮은 처리 비용으로 높은 성능과 처리량을 제공합니다. 마지막으로, 높은 병렬성 또한 가지고 있습니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

***

## Process Management
#### 프로세스 생성 과정에 대해 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    운영체제가 부팅되면 운영체제는 최조의 init 프로세스를 생성하고, 그 후에 생성되는 모든 사용자 프로세스는 fork 라는 시스템콜을 통해 부모 프로세스를 복제하여 자식 프로세스를 생성하는 방식으로 만들어집니다. 생성된 자식 프로세스는 exec 시스템콜을 통해 새로운 프로그램을 메모리에 덮어 씌운 후 해당 프로그램을 실행합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### IPC 메커니즘은 어떤 경우에 사용되는 것이 좋은지 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    IPC란 Interprocess Communication으로, 프로세스란 기본적으로 독자적인 주소 공간을 갖고 다른 프로세스의 영향을 주거나 받지 않는 것이 원칙이지만, 경우에 따라 프로세스 간의 통신과 동기화가 필요할 때 IPC를 활용하게 됩니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### IPC 메커니즘 중 간접적으로 메세지를 전달하는 방식은 어떠한 메세징 기법인지 대답해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    IPC의 기법 중 Message Passing 기법에는 direct/indrect 방식이 있는데, 이 중 간접적으로 메시지를 전달하는 방식인 indirect 방식은 통신하려는 프로세스의 이름을 명시적으로 표시하지 않고, mailbox나 port를 통해 간접적으로 전달합니다. 해당 mailbox나 port를 공유하는 프로세스 간의 통신이 가능합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### 프로세스와 관련된 시스템 콜 명령어 중 두 개를 골라 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    fork는 부모 프로세스를 복제하여 자식 프로세스를 생성하는 시스템콜, exec는 새로운 프로그램을 메모리에 덮어 씌워 실행하는 시스템콜, wait은 자식 프로세스의 작업이 끝날 때까지 부모 프로세스를 sleep 시켜 기다리게 하는 시스템콜, exit은 자원을 해제하고 부모에게 알리는 종료 시스템콜 입니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

***

## CPU Scheduling
#### Dispatcher의 역할은 무엇인가요?
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    Dispatcher란 CPU 스케줄러에 의해 선택된 프로세스에게 실제로 Context Switching을 통해 CPU 제어권을 넘겨주는 역할을 합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### Starvation(기아 상태)란 무엇인지 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    Starvation이란 특정 프로세스가 CPU를 할당받지 못하고 계속해서 무한정 기다리는 상황을 의미합니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### 선점형(Preemptive) 스케줄링과 비선점형(Non-preemptive) 스케줄링의 차이점을 설명하고 각각의 예시(FCFS, SJF 등의 스케줄링 알고리즘 중 선택)를 하나씩 들어주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    선점형 스케줄링은 특정 프로세스가 CPU를 차지하고 있고 해당 프로세스의 CPU 작업이 끝나지 않았더라도 다른 프로세스가 CPU 제어권을 강제로 빼앗을 수 있는 스케줄링이며, 그 예시로는 일정 할당 시간이 지나면 타이머 인터럽트를 통해 프로세스의 작업이 끝나지 않았더라도 프로세스에게서 CPU 제어권을 빼앗아 다른 프로세스에게 넘겨주는 Round Robin 스케줄링을 들 수 있습니다. 비선점형 스케줄링은 특정 프로세스가 CPU를 차지하고 있다면 해당 프로세스가 작업을 끝내고 CPU를 자진으로 반납할 때까지 다른 프로세스가 CPU를 할당받을 수 없는 스케줄링으로, 예시로는 ready queue에 도착한 순서대로 CPU를 할당 받고 사용하는 FCFS 스케줄링이 있습니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

#### Multilevel Queue와 Multilevel Feedback Queue를 비교하여 설명해주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    Multilevel Queue란 ready queue를 여러 개로 분할하여 관리하는 스케줄링으로, 분할된 큐마다 다른 스케줄링 알고리즘을 활용할 수 있으며, 큐 자체에 대한 스케줄링 알고리즘 또한 필요하다는 특징을 갖습니다. Multilevel Feedback Queue는 Multilevel Queue와 유사하게 ready queue를 여러 개로 분할하여 관리하는 것 분만 아니라 프로세스들이 큐 간에 이동할 수 있다는 특징이 있습니다. Multilevel Queue는 우선순위가 높은 큐에 프로세스가 남아있다면 우선순위가 낮은 큐에 들어있는 프로세스들은 starvation을 겪게되는 문제가 있는데, Multilevel Feedback Queue는 큐 간의 이동이 가능한 특징 및 Aging 기법을 활용하여 해당 문제점을 보완할 수 있습니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>

***

## Process Synchronization
#### Race Condition의 개념을 설명하고, OS에서 Race Condition이 발생할 수 있는 상황의 예시를 하나 들어주세요.
<details>
  <summary>박우람</summary>
  <div markdown="1">       
    👀
  </div>
</details>
<details>
  <summary>정다은</summary>
  <div markdown="1">
    Race Condition이란 다수의 프로세스가 하나의 공유 데이터를 접근하려고 경쟁하는 상황을 의미합니다. 예를 들어, 커널 모드로 수행 중일 때 인터럽트가 발생하면 인터럽트 처리 루틴 또한 커널 코드로 Kernel Address Space를 공유하기 때문에 Race Condition 및 데이터 불일치 문제가 수반될 수 있습니다.
  </div>
</details>
<details>
  <summary>정희윤</summary>
  <div markdown="1">       
    👀
  </div>
</details>
