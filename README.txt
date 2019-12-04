Student Name: Mariam Khaled Massadeh
Jordan University of Science and Technology
https://www.linkedin.com/in/mariammassadeh/
Doctor Khaldoun Mhaidat
Project Title: ARM Assembler
Project Description: A JS-based 2-pass assembler.


A two pass assembler does two passes over the source file;
(note that the second pass can be over an intermediate file generated in the first pass of the assembler).

	In the first pass:
		it looks for label definitions and introduces them in the symbol table;
			symbol table is a dynamic table which includes the label name and address for each label in the source program.

	In the second pass:
		after the symbol table is completed, it does the actual assembly by translating the operations into machine codes.





	Instruction List

			adc, add, and, b, bic, bl, cdb, cmn,
			cmp, eor, ldc, ldm, ldr,
			ldrb, mcr, mla, mov, mrc, mul, mvn,
			orr, rsb, rsc, sbc, stc, stm, str,
			strb, sub, swi, swp, swpb, teq, tst




	Registers List

			r0, r1, r2, r3, r4, r5, r6, r7, r8, r9, r10, r11, r12, r13, r14, r15




	Software Interrupts List

			0x00000000, 0x00000004, 0x00000008, 0x0000000C, 0x00000010, 0x00000014, 0x00000018, 0x0000001C