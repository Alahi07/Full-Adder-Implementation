`include "xor_gate.v"
`include "and_gate.v"
module ha(
  input wire a,
  input wire b,
  output wire s1,
  output wire c1);
  
  xor_gate u0(
    .a(a),
    .b(b),
    .y(s1)
  );
  and_gate u1(
    .a(a),
    .b(b),
    .y(c1)
  );
endmodule
