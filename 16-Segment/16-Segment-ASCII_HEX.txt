/*
 *  Project     Segmented LED Display - ASCII Library
 *  @author     David Madison
 *  @link       github.com/dmadison/Segmented-LED-Display-ASCII
 *  @license    MIT - Copyright (c) 2017 David Madison
 *
 * Permission is hereby granted, free of charge, to any person obtaining a copy
 * of this software and associated documentation files (the "Software"), to deal
 * in the Software without restriction, including without limitation the rights
 * to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 * copies of the Software, and to permit persons to whom the Software is
 * furnished to do so, subject to the following conditions:
 *
 * The above copyright notice and this permission notice shall be included in
 * all copies or substantial portions of the Software.
 *
 * THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 * IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 * FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 * AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 * LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 * OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 * THE SOFTWARE.
 *
 */
 
const uint32_t SixteenSegmentASCII[96] = {
	0x00000, /* (space) */
	0x1000C, /* ! */
	0x00204, /* " */
	0x0AA3C, /* # */
	0x0AABB, /* $ */
	0x0EE99, /* % */
	0x09371, /* & */
	0x00200, /* ' */
	0x01400, /* ( */
	0x04100, /* ) */
	0x0FF00, /* * */
	0x0AA00, /* + */
	0x04000, /* , */
	0x08800, /* - */
	0x10000, /* . */
	0x04400, /* / */
	0x044FF, /* 0 */
	0x0040C, /* 1 */
	0x08877, /* 2 */
	0x0083F, /* 3 */
	0x0888C, /* 4 */
	0x090B3, /* 5 */
	0x088FB, /* 6 */
	0x0000F, /* 7 */
	0x088FF, /* 8 */
	0x088BF, /* 9 */
	0x02200, /* : */
	0x04200, /* ; */
	0x09400, /* < */
	0x08830, /* = */
	0x04900, /* > */
	0x12807, /* ? */
	0x00AF7, /* @ */
	0x088CF, /* A */
	0x02A3F, /* B */
	0x000F3, /* C */
	0x0223F, /* D */
	0x080F3, /* E */
	0x080C3, /* F */
	0x008FB, /* G */
	0x088CC, /* H */
	0x02233, /* I */
	0x0007C, /* J */
	0x094C0, /* K */
	0x000F0, /* L */
	0x005CC, /* M */
	0x011CC, /* N */
	0x000FF, /* O */
	0x088C7, /* P */
	0x010FF, /* Q */
	0x098C7, /* R */
	0x088BB, /* S */
	0x02203, /* T */
	0x000FC, /* U */
	0x044C0, /* V */
	0x050CC, /* W */
	0x05500, /* X */
	0x088BC, /* Y */
	0x04433, /* Z */
	0x02212, /* [ */
	0x01100, /* \ */
	0x02221, /* ] */
	0x05000, /* ^ */
	0x00030, /* _ */
	0x00100, /* ` */
	0x0A070, /* a */
	0x0A0E0, /* b */
	0x08060, /* c */
	0x0281C, /* d */
	0x0C060, /* e */
	0x0AA02, /* f */
	0x0A2A1, /* g */
	0x0A0C0, /* h */
	0x02000, /* i */
	0x02260, /* j */
	0x03600, /* k */
	0x000C0, /* l */
	0x0A848, /* m */
	0x0A040, /* n */
	0x0A060, /* o */
	0x082C1, /* p */
	0x0A281, /* q */
	0x08040, /* r */
	0x0A0A1, /* s */
	0x080E0, /* t */
	0x02060, /* u */
	0x04040, /* v */
	0x05048, /* w */
	0x05500, /* x */
	0x00A1C, /* y */
	0x0C020, /* z */
	0x0A212, /* { */
	0x02200, /* | */
	0x02A21, /* } */
	0x0CC00, /* ~ */
	0x00000, /* (del) */
};
