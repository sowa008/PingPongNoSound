//---------------------------------------------------------------------------

#ifndef Unit1H
#define Unit1H
//---------------------------------------------------------------------------
#include <Classes.hpp>
#include <Controls.hpp>
#include <StdCtrls.hpp>
#include <Forms.hpp>
#include <ExtCtrls.hpp>
#include <jpeg.hpp>
#include <Graphics.hpp>
//---------------------------------------------------------------------------
class TForm1 : public TForm
{
__published:	// IDE-managed Components
        TImage *background;
        TImage *ball;
        TTimer *timerBall;
        TImage *leftBroom;
        TTimer *up;
        TTimer *down;
        TImage *rightBroom;
        TTimer *upright;
        TTimer *downright;
        TLabel *Label1;
        TLabel *Label2;
        TButton *Button1;
        TButton *Button2;
        TImage *bludger1;
        TTimer *timerBludger1;
        TImage *bludger2;
        TTimer *timerBludger2;
        TButton *Button3;
        void __fastcall FormKeyUp(TObject *Sender, WORD &Key,
          TShiftState Shift);
        void __fastcall FormKeyDown(TObject *Sender, WORD &Key,
          TShiftState Shift);
        void __fastcall timerBallTimer(TObject *Sender);
        void __fastcall upTimer(TObject *Sender);
        void __fastcall downTimer(TObject *Sender);
        void __fastcall uprightTimer(TObject *Sender);
        void __fastcall downrightTimer(TObject *Sender);
        void __fastcall Label1Click(TObject *Sender);
        void __fastcall Button2Click(TObject *Sender);
        void __fastcall Button1Click(TObject *Sender);
        void __fastcall timerBludger1Timer(TObject *Sender);
        void __fastcall timerBludger2Timer(TObject *Sender);
        void __fastcall FormClose(TObject *Sender, TCloseAction &Action);
        void __fastcall Button3Click(TObject *Sender);
private:	// User declarations
public:		// User declarations
        __fastcall TForm1(TComponent* Owner);
};
//---------------------------------------------------------------------------
extern PACKAGE TForm1 *Form1;
//---------------------------------------------------------------------------
#endif
