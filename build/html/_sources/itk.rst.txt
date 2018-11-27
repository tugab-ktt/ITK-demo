Инфо за дисциплината ИТК
=============================

What you will need
--------------------

For this project we are going to leave
the exact same circuit set up as in
Project 1, but will use some different
code to make the LED display a
message in Morse Code. In this case,
we are going to get the LED to signal
the letters S.O.S., which is the
international morse code distress signal.
Morse Code is a type of character
encoding that transmits letters and
numbers using patterns of On and Off. It
is therefore nicely suited to our digital
system as we can turn an LED on and
off in the necessary pattern to spell out
a word or a series of characters. In this
case we will be signaling S.O.S. which
in the Morse Code alphabet is three dits
(short flash), followed by three dahs
(long flash), followed by three dits again.
We can therefore now code our sketch
to flash the LED on and off in this
pattern, signaling SOS.

Enter the code
----------------

Create a new sketch and then type in
the code listed above. Verify your code
is error free and then upload it to your
Arduino.

Така изглежда нашата платка:

.. image:: /images/pcb.png
    :alt: PCB
    :target: https://www.tugab.bg/index.php?lang=bg

Така изглежда нашия код:
	
.. code::

	// Project 3 - Traffic Lights
	int ledDelay = 10000; // delay in between changes
	int redPin = 10;
	int yellowPin = 9;
	int greenPin = 8;
	void setup() {
	pinMode(redPin, OUTPUT);
	pinMode(yellowPin, OUTPUT);
	pinMode(greenPin, OUTPUT);
	}
	void loop() {

	
	
.. list-table:: Тable with 3 columns, header-row and stub-column and right alignment
     :widths: 15 10 20
     :header-rows: 1
     :stub-columns: 1
     :align: right

     * - Header 1
       - Header 2
       - Header 3
     * - Stub Row 1
       - Column 2, row 2
       - Column 3, row 2
     * - Stub Row 2
       - Column 2, row 3
       - Column 3, row 3
     * - Stub Row 3
       - Column 2, row 4
       - Column 3, row 4

Пример за списък:

* **Дефиниция 1**

  Дефиниция 1 се отнася за горния текст.

* ред 2

   - под ред 1
   - под ред 2


.. Important:: Важно

  .. Error:: Грешка

    .. Hint:: Подсказка

         .. Warning:: Предупреждение
         
         .. code::
         
            команди 
             команди