# $FreeBSD$

.include <bsd.own.mk>

LIB=	llvmasmprinter

SRCDIR=	lib/CodeGen/AsmPrinter
SRCS=	ARMException.cpp \
	AddressPool.cpp \
	AsmPrinter.cpp \
	AsmPrinterDwarf.cpp \
	AsmPrinterInlineAsm.cpp \
	DIE.cpp \
	DIEHash.cpp \
	DbgValueHistoryCalculator.cpp \
	DebugLocStream.cpp \
	DwarfAccelTable.cpp \
	DwarfCFIException.cpp \
	DwarfCompileUnit.cpp \
	DwarfDebug.cpp \
	DwarfExpression.cpp \
	DwarfFile.cpp \
	DwarfStringPool.cpp \
	DwarfUnit.cpp \
	EHStreamer.cpp \
	ErlangGCPrinter.cpp \
	OcamlGCPrinter.cpp \
	WinCodeViewLineTables.cpp \
	WinException.cpp

TGHDRS=	Attributes \
	Intrinsics

.include "../clang.lib.mk"
