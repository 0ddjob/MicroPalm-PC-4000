                      PC5000/PC4000 Utilities Disk

This short file contains information that was too recent to include
in the manual.  The file contains information on these topics:


Installing MPCLINK.SYS

Before you can transfer files between the PC/5000 and the PC, you must
install the MPCLINK.SYS device driver.  You install the device driver by
copying the file to the root directory of the PC boot disk (normally the hard
drive) and placing the command

	DEVICE=MPCLINK.SYS [/2] {[PARA][[COM[n]],[RATE]]}

in the last line of the PC CONFIG.SYS file.  Placing  the command in the last
line of the file lessens the possibility of conflict with other system setup
parameters, such as virtual drives in the PC.  The "DEVICE=MPCLINK.SYS"
command makes disk drive assignments on your PC.  The device driver allows
the PC/5000 to appear to your PC as two diskette drives, and assigns two or
four disk drive letters.

/2	This optional switch will allow the device driver to address two
	PC/5000 computers through the same communications port.  If only
	one PC/5000 is connected to the communications port, the "/2" 
	switch is not necessary.  Using the "/2" switch will assign two
	disk drive letters for each PC/5000.  You will therefor have two
	logical units (PC/5000s) with two diskette drives each, causing the
	device driver to use up four disk drive letters.

Default Communications Parameters.  Use these options to set the default
communications parameters to be used by the device driver.  If the options
are set,  it will not be necessary to include them in the CONNECT command
line (see "Selecting the PC/5000 for File Transfers" below)

PARA	Parallel transfer.  If a PC/5000 Parallel Adaptaer is installed in the
	PC, you can select parallel file transfers.  (You need not select a
	transfer rate if parallel communications are selected.)

COM[n]	Serial transfer communications port.  If a PC/5000 Parallel Adapter
	is not present in the PC, or if you want to communicate through
	another device such as a modem, you can select the serial
        communications port for file transfers.  If you select serial file
        transfers, you must also select the transfer rate as established in
        the PC/5000.

RATE	Baud rate.  If communications are serial, you select the transfer
	rate established in the PC/5000 communications parameters. 

Note:	If it is necessary for you to communicate with PC/5000s through more
than one communications port, you can install up to three copies of
MPCLINK.SYS by adding three "DEVICE=MPCLINK.SYS" commands to your CONFIG.SYS
file. This will allow up to six logical units (twelve disk letters) to be
connected at a time.

Using CONNECT.EXE

THe syntax for CONNECT is as follows:

CONNECT <l>,<[id#-unit#][ANY]>,{[PARA][[COMn],[RATE]]},[/N],[/V]

The syntax notation is the same as that used in the "PC/5000 MS/DOS User's
Guide".

l	Logical unit number.  This is the number associated with the pair of
	disk drive letters assigned when MPCLINK.SYS was installed at BOOT.
	If the last disk drive used by your PC befor MPCLINK.SYS was
	installed was drive C:, then logical unit 1 would be associated
	with drives D: and E:.  If the device driver was installed with the
	/2 switch, you would also have a logical unit 2 associated with
	drives F: and G:.

/V	Verbose switch.  Including this switch instructs the CONNECT program
	to display information about the communications parameters if that
	option was omitted from the command line.

Connect Information Messages

CONNECT - Succeeded.  System RAM=256k, Module 1=256k (D:), Module 2=1024k (E:)

	The PC/5000 specified in the command line answered the poll and has
	successfully connected to the PC.  Also, the answering PC/5000 is
	configured to have 256 kilobytes of system RAM, 256 kilobytes of
	memory in it's internal memory module (which can be referenced as
	disk drive D:), and 1024 kilobytes of memory in it's removable
	memory module (which can be referenced as disk drive E:).

CONNECT - 'ANY' processor polled.  Answering processor is 123-45678.

	This message indicates that 'ANY' was used for the processor number
	or the processor number was omitted from the command line, and that
	processor number 123-45678 was connected to the PC and answered the
	poll.

CONNECT - Connection is via parallel port.
			or
CONNECT - Connection is via Serial Port 1 at 19200 BPS.

	These are responses showing the previously set communications 
	parameters used by the CONNECT program when the /V switch was
	specified.

CONNECT - Date will NOT be set in PC5000 123-45678

	The /N no date set switch has been specified on the command line.

Connect Error Messages.

CONNECT - Logical Unit 1, Processor ID: 123-4567, on port: com1, at rate: 19200
CONNECT - Unable to contact PC5000. Procedure Terminated.

	The first message line echos the parameters that the CONNECT used
	to attempt to contact the specified PC/5000.  This line shows the
	default parameters used if the parameters were omitted from the
	command line.  The second line indicates that no response was
	received from the specified PC/5000, to the poll issued on the 
	specified communications port at the specified baud rate.

CONNECT - Logical unit must be a positive number.

	A non-numeric character was specified for the logical unit number.

CONNECT - Largest Logical Unit # = x

	An attempt has been made to use a Logical Unit Number larger then
	the number of Logical Units assigned by all the copies of MPCLINK.SYS
	installed at BOOT time.  x = 0 Indicates that no copies of MPCLINK.SYS
	have been successfully installed, or software installed after
	MPCLINK.SYS has removed the MPCLINK.SYS device driver from the
	operating system.

CONNECT - Invalid character [x] in Processor ID.
		and
CONNECT - Processor id value invalid.
		and
CONNECT - Group id value invalid.

	These three messages indicate an error in the PC/5000 ID number
	specification.  The ID number must be in the format ggg-uuuuu, where:
		ggg = A positive integer of 1 to 254 inclusive.
		uuuuu = A positive integer of 1 to 65534 inclusive.
	The dash (-) must be included.

CONNECT - Processor ID in use on drive [D] ...Disconnected.

	The PC/5000 with the ID number specified in the command line has
	previously been successfully connected using a different logical
	unit number (hence drive letter).  It has been disconnected from 
	it's previous logical unit and assigned the new logical unit.

CONNECT - Serial port specified without specifying rate
		and
CONNECT - Invalid character [c] in serial port speed.
		and
CONNECT - invalid serial port rate

	These three messages concern errors in the specification of the
	serial port baud rate.  If a serial communications port is selected
	in the command line, the baud rate must also be specified.  The
	baud rate must be selected from the following list:

		  110
		  300
		  600
		 1200
		 2400
		 4800
		 9600
		19200

CONNECT - Port is in use for other drives.

	An attempt has been made to connect logical units associated with
	two diferent copies of MPCLINK.SYS to the same communications port.
	Confilcts with hardware interrupt priorities prevent this from
	being done. 		

                              MODEM UTILITIES

     The modem utilities are provided to aid in the use of modem communica-
tions with the PC/5000 computer. MPCDIAL.EXE, MPCANSWR.EXE, HANGUP.EXE and
MPCRETA.EXE are used on the host PC to initiate communications with a remote
hand held computer.  HHCDIAL.EXE and HHCANSWR.EXE are used on the PC/5000 to
initiate communications with a host PC.

				ON THE PC

INITIALIZING THE COMM PORT:

     Before using MPCDIAL or MPCANSWR on a PC it is necessary to initialize
the comm port that will be used with your modem by using the mode command.
For example:
              MODE COM1:1200,N,8,1

sets the com1 port to 1200 baud, no parity, 8 data bits, and one stop bit.
In MPCDIAL, MPCANSWR and HANGUP, the Com1 or Com2 parameters and the
modem_command_string are optional.  In the command string a ^n produces a 
delay of n seconds before the rest of the string is sent to the modem.  This 
is useful for adding necessary pauses to the command (i.e. ^1+++^1 to send 
an escape sequence to a Hayes compatable modem.)

PC Dial command:

              MPCDIAL < com1 | com2 >  modem_command_string

PC Answer command:

              MPCANSWR < com1 | com2 >  modem_command_string

PC Hangup command:

              HANGUP < com1 | com2 >  modem_command_string

PC command to Return to Application:

	      MPCRETA

     The programs all return an error code of zero if they are successful and
an error code of 1 if they are not successful.  They also display any
messages returned by the modem.  All output from the commands is through
Standard Out so that the responses can be redirected to a file.

  			    ON THE PC/5000

INITIALIZING THE COMM PORT:

     The PC/5000 serial port parameters are determined by the Set Comm 
Parameters function in the ROM MONITOR.  The HHC programs immediately enter
communications mode after a successful connection is established.

PC/5000 Dial command:

              HHCDIAL   modem_command_string

PC/5000 Answer command:

              HHCANSWR   modem_command_string

                           MPC TERMINAL EMULATOR


Purpose:

To allow use of the PC as terminal to a handheld.  There are times
when it is desirable to use the PC's keyboard rather than that of the
handheld (e.g., when debugging an application).  Further, it can be
useful to dial into a handheld remotely for problem determination.  
In either case, the PC, in this view, is used as a terminal.

The implementation depends on the use of the CTTY command at the
handheld.  CTTY causes DOS to redirect CON input and output.  As the
name indicates, it operates in simple TTY mode, i.e. there are no
function keys and the whole interchange consists of ASCII characters
plus carriage return and line feed.  In sum, no full screen handling.  
It is useful for DEBUG and DOS commands as well as any application
which communicates through standard DOS console I/O calls.

The syntax of CTTY allows redirection to a serial port and an MPC
local modification additionally allows redirection to the handheld
parallel port.  For these purposes the device "AUX" which is normally
identical to COM1 is caused to use handheld BIOS calls for parallel
I/O.

Thus "CTTY COM1"causes DOS to "talk to" the serial port and "CTTY
AUX" does the same for the parallel port.

Given that the goal was to provide the user with a facility that
would allow the use of a PC as a terminal, the requirement was to
provide a bare-bones terminal emulator that would be relatively easy 
to use and would substitute for a more pricey feature-rich product 
such as Crosstalk or other software packages.  

Thus the resulting terminal emulator is a teletype emulator with
features as described below.  


PROGRAM INVOCATION

The emulator is a standard MS-DOS program which accepts a single
command-line parameter.  That parameter is "COMMx" (where x is 1 -
4) or "PARA".  The parameter is optional.

On the handheld side there are two steps.  Since the handheld BIOS
does not allow serial port I/O without a preceeding initialization
call, a little program called "TURNON" is run which issues an INT
14h, Function 0 call using the parameters set in the Set Comm Parameters
function in the ROM MONITOR.  Then CTTY COM1 or CTTY PARA is issued.


Once the PC program is invoked, certain function keys are available:


F1 = COM1 	Select Port


F2 = COM2 	Select Port


F3 = COM3 	Select Port


F4 = COM4 	Select Port


F5 = PARA 	Select Port


F6 = LOG	Specifies that all lines received from the handheld
    		are echoed to file or device.  The default device is 
		PRN.  Since communication to the handheld is echoed,
		this effectively logs the session.  F6 is a "toggle",
		alternately turning LOG off and on.

F7 = Define	Allows the entry of a log file (or device) name.


F8 = Shell 	Transfers control to secondary copy of COMMAND.COM or
		other shell.  "EXIT" of course returns control to the
		Terminal Emulator.


F10 = End	Terminates the session.



A HELP line is displayed at the bottom of the Terminal Emulator screen,
enumerating these functions.  The remainder of the line feeds back
the name of the current log file.  When the logging function is
active, the colon in the name field blinks.

            DIRECT COMMUNICATIONS PROGRAM LOAD INTERFACE


PURPOSE:

To preclude the necessity of storing large executable program
files on the PC/5000 RAM Disk modules, the MPCLOAD program is
intended to allow the user of the PC/5000 to load and execute a
program from the communications interface without transferring the
executable file to the PC/5000 RAM Disk storage.

USAGE:

To use this facility, the PC/5000 must be connected to the
communications interface device and must have completed a valid
"POLL" sequence (this can be accomplished through the use of the
CONNECT program - see CONNECT PROGRAM INTERFACE).

COMMAND FORMAT:

        MPCLOAD PGM-SPEC N

        MPCLOAD         Program name (required)


        PGM-SPEC        Path, (if omitted, the program will use
                        the current default path) program name and
                        any parameters that are needed to execute
                        the program on the PC/5000.

        N               Logical unit number of a previously
                        "CONNECTED" PC/5000.


EXAMPLE:

        1.    CONNECT 1,10-123,PARA
        2.    MPCLOAD C:\ASM\EDLIN B:AUTOEXEC.BAT

        This sequence of commands:

        1.    Issues a "POLL" to PC/5000 number 10-123 connected
              to the parallel communications device and designates
              this PC/5000 as logical unit 1. 

        2.    Loads the program EDLIN from Host P/C disk drive C:
              directory ASM into PC/5000 10-123 (previously
              designated as logical unit).  EDLIN will access the
              file AUTOEXEC.BAT from the internal RAM disk B: of the
              PC/5000.  The optional parameter (B:AUTOEXEC.BAT) tells
              EDLIN the name of the file to edit.  The parameters are
              typed the same way they would be entered on the command
              line after the program name.

The following change has been made to the BIOS ROM Ver. 2.1.  This change is
not yet reflected in the tech reference manual.

FORMAT  now responds with the message

FORMAT MEMORY MODULE
or SYSTEM MEMORY
Drive B:, C: or S

Each of these choices result in different set of messages being displayed.

Choice B formates the internal module as a B: drive and allows the user to
     allocate memory from the internal module to System RAM.  The Volume label
     for this and C drive are MPC0000####.

Choice C formates the external module as drive C:. 

Choice S formates a B: drive using the top of System RAM.  Some of which
     may have already been allocated from the internal module using choice B
     first.  The maximum size for this Vdisk drive is (704k-64k)=640k. The
     Volume for this drive is now MPCVDSK####.

ESC Key will exit from here with no damage to the drive's files

 
4. User has chosen B, C or S

     FORMAT responds with 
	112 or 224 Directory
	Entries(1-2)?:

The user can choose the maximum number of files possible on the root directory.
Choosing the smaller number gives the user more file space.

The ESC key allows the user to exit now with no damage to drive (last chance!)


5.
	after selection FORMAT responds with
       "SIZING DRIVE B (or C)"

	FORMAT is now sizing and testing the available memory in 16k byte 
	blocks for the module or System RAM.  If it detects an error
	in a block or memory, FORMAT flags the entire block as bad. 
	System Memroy is sized starting at the low 64k boundary and is sized
	up through any allocated memory. (64k is the default minimum System RAM)

	When FORMAT finishes sizing the memory module, it shows you a memory
        map of the sized module or RAM in 16k blocks: periods(.) represent
        good blocks and asterisks (*) represent blocks containing memory
        errors.
 
6a.      If B selection FORMAT responds with

       "Number of 16k Blocks
	SYSTEM RAM(0-nn):"

        The user may now enter the number 16k blocks (up to nn) to be
        allocated for use as System RAM. 

	The unit then reponsed with FORMATTING DRIVE. After a short wait
	a report is generated having the following format:
	   nnnnnn Bad 16-k Blocks
	   nnnnnn Total Blocks
		-Module Size-
	   nnnnnn Total Bytes
	   nnnnnn RAM Disk
           nnnnnn System RAM
	   nnnnnn Bad Tracks
	You see the size of the memory module and disk storage in bytes.  If
        you allocated a portion of memory module to system memroy, you see the
	amount of system RAM allocated in bytes.  Finally, if FORMAT detects
	any memory errors, it reports the size of the unusable area in bytes.

   
6b.   If selection C, FORMAT respondes as above but leaves out the
	choice for allocating System RAM.

6c.   If selection S, FORMAT respondes with 
	"# of 16k Blocks
         for VDISK ?(o-nn):"
      The user must choose the size for his vdisk.  The maximum allowable
      is nn which still leaves 64k for system memory.  
      FORMAT responds with FORMATTING DRIVE.  After a short wait
      a report is generated with the following format:
	nnnnn Bad Blocks
	nnnnn Ram Disk
	nnnnn Bad Tracks

7.  Last message:
	"Format Again (y/n)?"


    If a system memory allocation or a vdisk was involved the unit
    may do a cold boot on exit from FORMAT because COMMAND.COM may no 
    longer be resident in upper memory.	

	

