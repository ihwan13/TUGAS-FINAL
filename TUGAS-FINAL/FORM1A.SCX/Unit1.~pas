unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, ExtCtrls;

type
  TForm1 = class(TForm)
    Panel1: TPanel;
    Label1: TLabel;
    GroupBox1: TGroupBox;
    Label2: TLabel;
    Edit1: TEdit;
    Label3: TLabel;
    Label4: TLabel;
    Edit2: TEdit;
    Edit3: TEdit;
    GroupBox2: TGroupBox;
    Label5: TLabel;
    Edit4: TEdit;
    Button1: TButton;
    Button2: TButton;
    Label6: TLabel;
    Button3: TButton;
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure Button1Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

procedure TForm1.Button2Click(Sender: TObject);
begin
Edit1.clear;
Edit2.clear;
Edit3.clear;
end;

procedure TForm1.Button3Click(Sender: TObject);
begin
close
end;

procedure TForm1.Button1Click(Sender: TObject);
begin
Edit4.Text := floattostr (strtoint (Edit2.Text) * strtoint (Edit3.Text))+'.00';
end;

end.
