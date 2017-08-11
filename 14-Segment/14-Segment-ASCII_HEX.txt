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
 
const uint16_t FourteenSegmentASCII[96] = {
	0x0000, /* (space) */
	0x4006, /* ! */
	0x0202, /* " */
	0x12CE, /* # */
	0x12ED, /* $ */
	0x3FE4, /* % */
	0x2359, /* & */
	0x0200, /* ' */
	0x2400, /* ( */
	0x0900, /* ) */
	0x3FC0, /* * */
	0x12C0, /* + */
	0x0800, /* , */
	0x00C0, /* - */
	0x4000, /* . */
	0x0C00, /* / */
	0x0C3F, /* 0 */
	0x0406, /* 1 */
	0x00DB, /* 2 */
	0x008F, /* 3 */
	0x00E6, /* 4 */
	0x2069, /* 5 */
	0x00FD, /* 6 */
	0x0007, /* 7 */
	0x00FF, /* 8 */
	0x00EF, /* 9 */
	0x1200, /* : */
	0x0A00, /* ; */
	0x2440, /* < */
	0x00C8, /* = */
	0x0980, /* > */
	0x5083, /* ? */
	0x02BB, /* @ */
	0x00F7, /* A */
	0x128F, /* B */
	0x0039, /* C */
	0x120F, /* D */
	0x0079, /* E */
	0x0071, /* F */
	0x00BD, /* G */
	0x00F6, /* H */
	0x1209, /* I */
	0x001E, /* J */
	0x2470, /* K */
	0x0038, /* L */
	0x0536, /* M */
	0x2136, /* N */
	0x003F, /* O */
	0x00F3, /* P */
	0x203F, /* Q */
	0x20F3, /* R */
	0x00ED, /* S */
	0x1201, /* T */
	0x003E, /* U */
	0x0C30, /* V */
	0x2836, /* W */
	0x2D00, /* X */
	0x00EE, /* Y */
	0x0C09, /* Z */
	0x0039, /* [ */
	0x2100, /* \ */
	0x000F, /* ] */
	0x2800, /* ^ */
	0x0008, /* _ */
	0x0100, /* ` */
	0x1058, /* a */
	0x2078, /* b */
	0x00D8, /* c */
	0x088E, /* d */
	0x0858, /* e */
	0x14C0, /* f */
	0x048E, /* g */
	0x1070, /* h */
	0x1000, /* i */
	0x0A10, /* j */
	0x3600, /* k */
	0x0030, /* l */
	0x10D4, /* m */
	0x1050, /* n */
	0x00DC, /* o */
	0x0170, /* p */
	0x0486, /* q */
	0x0050, /* r */
	0x2088, /* s */
	0x0078, /* t */
	0x001C, /* u */
	0x0810, /* v */
	0x2814, /* w */
	0x2D00, /* x */
	0x028E, /* y */
	0x0848, /* z */
	0x0949, /* { */
	0x1200, /* | */
	0x2489, /* } */
	0x0CC0, /* ~ */
	0x0000, /* (del) */
};
