`include "ha.v"
`include "or_gate.v"

module fa(
  input wire a,
  input wire b,
  input wire cin,
  output wire sum,
  output wire carry);
  wire w1,w2,w3;
  ha u0(
    .a(a),
    .b(b),
    .s1(w1),
    .c1(w2)
  );
  ha u2(
    .a(w1),
    .b(cin),
    .s1(sum),
    .c1(w3)
  );
    
  or_gate u3(
    .a(w3),
    .b(w2),
    .y(carry)
  );
endmodule
